# Store Sales - Time Series Forecasting

This repository contains the code for the Kaggle competition [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/). The goal of the competition is to predict the sales of multiple product families and Ecuadorian stores.

The selected approach is hybrid model combining linear regression with a random forest regressor. The linear regression model is fit for trend, fourier terms and holiday indicators (holidays affect sales). The random forest model is fit for the residuals of the linear regression model. The solution is inspired by the Kaggle [time series course](https://www.kaggle.com/learn/time-series).