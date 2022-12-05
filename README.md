# timeseries_arima_prediction
Consider that we need some fast prediction of timeseries. Here I'm going to use ARIMA, which requires a lot of different input values: we have to estimate acf, pacf, AIC, etc.  In this case, I'm going to unify the approach for fast selecting these attributes, using only the proportion between train and test samples and the number of steps for further prediction.
