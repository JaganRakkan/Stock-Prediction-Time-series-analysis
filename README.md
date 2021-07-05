# Stock-Prediction-Time-series-analysis
Time series analysis is a statistical technique that deals with time series data, or trend analysis.
In this case we use Tesla stock price of past years.
In this code we use Auto-arima model.
ARIMA is a very popular statistical method for time series forecasting. ARIMA models take into account the past values to predict the future values. There are three important parameters in ARIMA:

           1. p (past values used for forecasting the next value), 
            
           2. q (past forecast errors used to predict the future values), d (order of differencing)

            3.Parameter tuning for ARIMA consumes a lot of time. So we will use auto ARIMA which automatically selects the best combination of (p,q,d) that provides the               least error.
