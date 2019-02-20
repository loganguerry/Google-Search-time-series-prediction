## Google Trends Time Series Analysis
This repo logs my steps in analysing Google Trends (time series search data) for a given company. I chose to explore Home Depot, on the assumption that seasonality and weather paterns may play an active role, and may be ultimately predictable. 

#### Steps:
  1. (NOT NECESSARY) Run "Initial Data Pull, ADF Tests..." notebook to pull and write data for Home Depot - the same CSV that is present in this repo titled "homedepot_googletrends.csv".
  2. Run "Prophet Time Series Analysis" notebook.
      1. loads existing CSV
      2. performs a variety of analytic reports and visualizations on Google Trends data for Home Depot

  3. Use "Addressing Holiday Weekend..." notebook to explore the effect of specific holoiday weekends and explore the largest outliers
  
#### Working:
  * Predictive modeling for apparent seasonality
  * Consider how to incorporate weather and holiday data
