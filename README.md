# Comparative Analysis of Time Series Splitting Criteria with Classical Statistics, Machine Learning, and Deep Learning

Comparative evaluation of different time series splitting strategies on forecasting models using the UCI Appliances Energy Prediction dataset.

## Project Overview
Developed as an undergraduate statistics capstone project. This study evaluates how data splitting criteria (Hold-out, Sliding Window, Expanding Window) impact the forecasting performance of ARIMA, Random Forest, and LSTM (with MIMO forecasting) models for household energy consumption.

## Key Highlights & Results
* **Dataset:** UCI Appliances Energy Prediction dataset.
* **Models Tested:** ARIMA, Random Forest, and LSTM with **MIMO (Multi-Input Multi-Output)** forecasting strategy.
* **Best Performing Approach:** LSTM combined with the expanding window strategy achieved the lowest RMSE, successfully capturing complex temporal dependencies and energy consumption patterns.

## Tech Stack
* **Language:** Python
* **Libraries:** PyTorch, Scikit-Learn, Statsmodels, Pandas, NumPy, Matplotlib
