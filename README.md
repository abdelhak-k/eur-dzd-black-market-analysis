# EUR/DZD Black Market Analysis

## Overview
This project analyzes the evolution of the EUR/DZD black market exchange rate in Algeria and provides short-term forecasts. It combines data analysis with economic context to explain the main drivers behind currency fluctuations in the parallel market.


## Data
- The data was collected using the [Eurodz](https://eurodz.com/) API, which provides historical black market exchange rates alongside official rates. The analysis covers the period from 2016 to March 2026.
- You will find the full collected data [here](https://www.kaggle.com/datasets/kadouciabdelhak/eurdzd-black-market-rate-time-series) (kaggle).
- ~~The [API](https://eurodz.com/api/data-294a869b196799a4.json) returns the historical EURO/DZD market exchange rates with the fields (date, buyRate, sellRate, officialBuyRate, officialSellRate) as a .json file~~ -> The API url changes every day :(

## Approach
- ~~Fetched the data directly from the [API](https://eurodz.com/api/data-294a869b196799a4.json)~~, used only the Date and SellRate columns, and filtered up to March 2026 since the analysis was done on 20 March 2026.
- Cleaned and structured the time series data
- Visualized long-term trends and major fluctuations  
- Linked key movements to economic and policy events in Algeria  
- Built a forecasting model to estimate future exchange rate behavior  

  [See notebook Github](Notebook.ipynb) / [See notebook Kaggle](https://www.kaggle.com/code/kadouciabdelhak/eur-dzd-black-market-rate-time-series-analysis) 


## Key Insights
- The black market exchange rate shows a clear long-term upward trend  
- Short-term movements are strongly influenced by government policies and market uncertainty  


## Results
The model provides consistent short-term forecasts and captures the general direction of the exchange rate, while highlighting the importance of external economic factors.


## Full Report
A detailed analysis, including methodology and extended results, is available in the full report:

[See Report](Report.pdf)
