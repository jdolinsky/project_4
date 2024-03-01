# Price Prediction for Microsoft Stock
#### by Alyssa Cullinan, Jacob Dolinsky, Jian Qiang Liu, Shubhangi Bidkar, Shunjia Liu

## Overview
In this project we used Machine Learning with several techniques and model types to predict the Microsoft (MSFT) stock price based on 5 years of historical data.  

Microsoft Corporation is an American multinational technology corporation headquartered in Redmond, Washington. Microsoft was founded in 1975 and went public in March 13, 1986. We picked Microsoft because we can get almost 38 years of the historical data for the stock price. 

In the first part of the project we conducted exploratory analysis for the adjusted stock price, volume, and percent change overtime using pandas and Plotly libraries.

![Image](/graphs/price_overtime.png)

![Image](/graphs/change_rate_price_volume.png)

We also used a candlestick chart to illustrate the daily price move.

![Image](/graphs/image.png)

The second part was Machine Learning analysis that included data preparation, model fitting and evaluation.

## Data Source
We used the Tiingo Web API to access historical stock market data. Tiingo is an Enterprise-Grade Financial Markets API with both raw and adjusted prices. The Tiingo database gives you access to one of the most expansive data sets available for US. 

Google Slides presentation can be found [here](https://docs.google.com/presentation/d/1FGnDJJqJxHiNHcKKDfNgYyHTlCyX_IzrqFZKsgJAn1k/edit?usp=sharing)