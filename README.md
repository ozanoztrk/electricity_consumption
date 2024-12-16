# Electricity Consumption Forecasting

A comprehensive comparison of different machine learning and statistical models for electricity consumption forecasting. The project implements and evaluates multiple models including Fused Lasso, XGBoost, ElasticNet.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13aUCxN6sjWq_33UeqmDgWDv2b8k54Szx?usp=sharing)

## Overview

This project focuses on forecasting electricity consumption using various time series forecasting techniques. It includes:

- Feature engineering for time series data
- Implementation of multiple forecasting models
- Cross-validation using TimeSeriesSplit
- Comprehensive model evaluation and comparison
- Interactive visualizations using Plotly

## Models Implemented

- Fused Lasso (with CVXPY optimization)
- XGBoost
- ElasticNet

## Features

- Time-based feature engineering (hour, day, month, weekend indicators)
- Lag features and rolling statistics
- Cyclical encoding of time features
- Robust scaling of features and target variables
- Cross-validation with time series split
- Comprehensive metrics (MSE, RMSE, MAE, MAPE, MASE, R²)
- Interactive visualization of predictions and model comparisons
