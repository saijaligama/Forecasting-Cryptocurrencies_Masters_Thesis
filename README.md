# Forecasting-Cryptocurrencies_Masters_Thesis
•	The aim was to predict the prices of three cryptocurrencies Bitcoin, Litecoin and Ethereum using Time Series Modelling with daily closing price from 16th of October 2018 to 9th of September 2021for a total of 1073 days. 
•	Conducted Exploratory data analysis using Matplotlib in python. Tried to identify crucial features responsible for price activity.
•	Cleaned data and identified outliers to understand the reason behind the outliers. Conducted Stationarity check using Augmented Dickey Fuller test and used Differencing to convert time series into stationary. 
•	Split the time series into trend, seasonality and residuals using the decomposition technique to confirm there is trend and seasonality.
•	Selected the appropriate lags for the ARIMA model by using the BIC(Bayesian Information Criterion) and also with the help of the Auto Correlation Function and Partial Auto correlation function plots.
•	Built and ARIMA model using python to predict closing prices of the cryptocurrencies.
•	Also used the PROPHET model developed by Facebook engineers which is known for its efficiency in analyzing seasonality and making forecasts.
•	Utilized the ARIMA time series model and the PROPHET model to forecast closing prices for the three cryptocurrencies.
