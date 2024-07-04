# Arima-Model
Logic: ARIMA (AutoRegressive Integrated Moving Average) models time series data by capturing autocorrelations and differencing the series to make it stationary.
Description: ARIMA combines autoregression (AR), differencing (I), and moving average (MA) to forecast future values, denoted as ARIMA(p,d,q) where 
p is the lag order,d is the degree of differencing, and q is the order of the moving average.
Basically used for time series forecasting.

Example 1: Forecasting daily temperature based on historical weather data.
Example 2: Predicting future inventory levels based on past sales trends and seasonality.
Example 3: Forecasting monthly sales figures for the next year based on historical sales data.

In the above code we use the Arima model to determine, future sales (jun-24) from sales-quantity, MRP and Discount.
