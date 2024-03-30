The Prediction approach for stock market volatility, which is based on time is consisted out of several forecasting models:
AutoRegressive (AR)
Moving Average (MA)
AutoRegressive Moving Average (ARMA)
AutoRegressive Integrated Moving Average (ARIMA)

This methods use the stationaroty of the data, so before using this approaches, the data, NIFTY 500 and SENSEX indeces, is tested for
stationarity with the ACF (Autocorrelation function) and PCF (partial correlation function), which also helped to find the optimal
parameters for MA and AR. To check the correlation of the residuals, the L-Jung-Box test was performed.

As an EXTRA OUTCOME, we implemented an LSTM model for forecastin the NIFTY 500 and Sensex indeces, since it is a RNN, which captures long-term dependencies
and compelx patterns.
