# SARIMA-vs-PROPHET
Model Comparison between SARIMA and FB Prophet for stock market data
When comparing SARIMA (Seasonal AutoRegressive Integrated Moving Average) and Prophet for stock market data, both models offer different advantages and drawbacks depending on the characteristics of the data and forecasting needs:

SARIMA is more appropriate if the stock market data exhibits strong autocorrelations and seasonal effects (e.g., quarterly cycles). However, SARIMA’s assumption of constant volatility and its complexity in tuning make it less suited for the volatile nature of stock prices.

Prophet, on the other hand, is more flexible and handles trend shifts better, making it ideal for stock market data that experiences sudden jumps and non-linear trends. While not perfect for short-term forecasts, Prophet’s ease of use and handling of non-stationarity make it a better fit for general stock market trend forecasting, especially for medium- to long-term horizons.
