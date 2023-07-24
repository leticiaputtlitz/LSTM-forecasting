# LSTM-forecasting
This work consists of a study on the application of Long Short-Term Memory (LSTM) networks for time series forecasting using a database from the National Treasury of Brazil. LSTM is a special case of the Recurrent Neural Network (RNN) method, which was initially introduced by Hochreiter and Schmidhuber \cite{Hochreiter97}. Time series forecasting is a challenging task due to the complexity of temporal patterns and the dependence on past data. In this context, LSTM networks are a good approach due to their ability to learn and remember long-term patterns. In this study, we use a database obtained from the Ministry of Finance for the forecasting. Comparatively, we apply the LSTM model, the Autoregressive Integrated Moving Average (ARIMA) model and the Seasonal Autoregressive Integrated Moving Average (SARIMA), as both the ARIMA and SARIMA models are widely used traditional methods for time series forecasting.

Main Objectives

* Compare the LSTM, ARIMA and SARIMA methods in terms of forecasting quality and performance.
* Identify the components of the time series: trend, seasonality, and random component.
* Create a Python code to train an LSTM and model both the ARIMA and SARIMA.
* Analyze the influence of hyperparameter choices for neural network training: epochs, neurons, hidden layers.
* Identify the best fit we could get of the LSTM to the data.
