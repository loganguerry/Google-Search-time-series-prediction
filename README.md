## Google Trends Time Series Analysis
This repo logs my steps in analysing Google Trends (time series search data) for a given company. I chose to explore Home Depot, on the assumption that seasonality and weather paterns may play an active role, and may be ultimately predictable. 

#### Steps:
  1. (NOT NECESSARY) Run "Initial Data Pull, ADF Tests..." notebook to pull and write data for Home Depot - the same CSV that is present in this repo titled "homedepot_googletrends.csv". Data pull requires API key, so just use the aforementioned CSV is you do not have one.
  2. "Prophet Time Series Analysis" notebook
      1. loads existing CSV
      2. performs a variety of analytic reports and visualizations on Google Trends data for Home Depot

  3. "Addressing Holiday Weekend..." notebook explores the effect of specific holoiday weekends and explore the largest outliers
  4. "Ad Spend Data Clean Up..." notebook incorporates ad spend data for Home Depot and aggregates it by week
  5. "Identifying Lag Correlation..." notebook prepares CSV of lagged ad spend and values - effectively a training set
  
#### Working:
  * Predictive modeling for apparent seasonality
  * Consider how to incorporate weather data on assumption that better weather means more home improvement projects and more searches for Home Depot
