**STOCK MARKET PREDICTION USING TIME SERIES ANALYSIS**

The stock market is a marketplace that allows for the seamless exchange of corporate stock purchases and sales. Every Stock Exchange has its own value for the Stock Index. The index is the average value derived by adding up the prices of various equities. This aids in the representation of the entire stock market as well as the forecasting of market movement over time. As a result, effectively predicting stock trends can reduce the risk of loss while increasing profit.

Time-series prediction is a common technique widely used in many real-world applications such as weather forecasting and financial market prediction. It uses the continuous data in a period of time to predict the result in the next time unit. Many time series prediction algorithms have shown their effectiveness in practice. Stock market is a typical area that presents time-series data and many researchers study on it and proposed various models. In this project, ARIMA model is used to forecast the stock price.

**ARIMA MODEL**

**(Auto Regressive Integrated Moving Average)**

A time series is sequence where a metric is recorded over regular time intervals. Depending on the frequency, a time series can be of yearly, monthly, weekly, hourly, minutes and even seconds wise. 
ARIMA is actually a class of models that explains a given time series based on its own past values, that is , its own lags and the lagged forecast errors, so that equation can be used to forecast future values. 
Any non-seasonal time series that exhibits patterns and is not a random white noise can be modeled with ARIMA models.
An ARIMA model is characterized by 3 items: p, d, q where,

i)‘p’ is the order of the AR term

ii)‘q’ is the order of the MA term

iii)d is the number of differencing required to make the time series stationary.
