# Time-series-forecasting
Multi step single/multi variate time series forecasting

This repository contains code for time series forecasting using Long Short-Term Memory (LSTM) networks. The code is implemented in TensorFlow and focuses on both univariate and multivariate time series forecasting.

Introduction
Time series forecasting is a crucial task in various domains, including weather prediction, stock market analysis, and traffic forecasting. This repository demonstrates the use of LSTM networks for both univariate and multivariate time series forecasting.

Setup
Before running the code, make sure you have the required dependencies installed. You can install them using the following command:

Data Loading and Exploration
The code uses the Climate dataset. The dataset is loaded, and basic exploration is performed to understand its structure.

Univariate Time Series Forecasting
The initial part of the code focuses on univariate time series forecasting, where the temperature is considered as the target variable. The data is preprocessed and visualized to create a univariate time series model.

Simple LSTM Model
A simple LSTM model is implemented for univariate time series forecasting. The model is trained, and its predictions are evaluated. Early stopping is applied to prevent overfitting.

Multivariate Time Series Forecasting
The code then transitions to multivariate time series forecasting, considering additional features such as atmospheric pressure and air density. The dataset is preprocessed, and a model is developed for both single-step and multi-step forecasting.

Single Step Forecast
A model for single-step forecasting is implemented and evaluated. The training history is visualized to understand the model's performance.

Multi-Step Forecast
The final part of the code focuses on multi-step forecasting using a more complex LSTM architecture. The model is trained, and its predictions are evaluated using visualizations.

Model Training and Evaluation
The training process involves the use of early stopping to prevent overfitting. Training and validation loss are monitored to assess the model's performance. Visualizations are provided to compare true future values with predicted values.

Conclusion
This code demonstrates the implementation of LSTM networks for both univariate and multivariate time series forecasting. Users can adapt the code to their specific datasets and experiment with different model architectures and hyperparameters. The provided visualizations aid in understanding the model's predictions and performance.
