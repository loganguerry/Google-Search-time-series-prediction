## Google Trends Time Series Analysis
This repo logs my steps in analysing Google Trends (time series search data) for a given company. I chose to explore Home Depot, on the assumption that seasonality and weather paterns may play an active role, and may be ultimately predictable. 

#### Steps:
  1. (NOT NECESSARY) Run first notebook "homedepot_capture-and-ADF_test" capture Google Trends data for Home Depot and writes the same CSV that is present in this repo.
  2. Run "Prophet Time Series Analysis" notebook.

      1. loads existing CSV
      2. performs a variety of analytic reports and visualizations on Google Trends data for Home Depot

#### Working:
  * Predictive modeling for apparent seasonality
  * Consider how to incorporate weather and holiday data
