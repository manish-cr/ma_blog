---
title: Baltimore Crime data
---

<img src="https://cdn.britannica.com/90/77990-050-E6087086/Inner-Harbor-skyline-Baltimore-Maryland.jpg" width="400" height="300" alt="Baltimore">  
*Baltimore*

### Baltimore crime forecasting

I have recently started learning time series and a fascinating technique that I have learnt was Holt-Winters method. It is an exponential time series that accounts for residuals in decreasing priority. [More info here](https://otexts.com/fpp2/holt-winters.html).  

It is good for short-term forecasting. As such, I made a 1 month forecast and noticed a downward trend. However, there are some **improvements** to be made:  
- Outlier detection (eliminating outliers to make less variant model)
- Comparative analysis (with ARIMA, VectorAutoregression, LSTM, XGBOOST etc.)
- In-sample/Out-sample prediction
- Diagnostic analysis (to tune the model better)

Here is [my code](https://github.com/manish-cr/data-science-projects/blob/master/Baltimore%20Crime%20Rate/src/Baltimore%20Crime%20Rate%20Forecast.ipynb)