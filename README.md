# Predicting-COVID-19-Hospitalizations
Predicting COVID-19 Hospitalizations

The purpose of this project is to predict the daily hospitalizations in Arizona from 3/8/21 - 3/14/21

Training data: https://covidtracking.com/
Testing data: https://www.azdhs.gov/covid19/data/index.php#hospitalization


We will explore using an ARMA model and an ARIMA model for time series forecasting.  

ARIMA Forecasting

    p = number of lag observations included in the model (lag order)
    d = number of times that the raw observations are differences (degree of differencing)
    q = size of moving average window (order of moving average)

# Note, ARMA is an ARIMA model with the d parameter set to 0

We will use Grid Search for hyperparameter tuning, to select optimal values of p, d, and q using the Root Mean Squared Error (RMSE) as the error statistic.
