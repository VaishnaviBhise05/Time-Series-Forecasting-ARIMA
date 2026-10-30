# Time Series Forecasting with ARIMA

## Overview
This project implements a time series forecasting pipeline using Python and ARIMA. It analyzes historical demand data, examines trends and seasonality, tests stationarity, and generates future forecasts.

## Objectives
- Visualize historical time series data.
- Decompose the series into trend, seasonal, and residual components.
- Perform the Augmented Dickey-Fuller (ADF) test.
- Select an ARIMA model using Akaike Information Criterion (AIC).
- Evaluate predictions using forecasting error metrics.
- Generate a 30-day future demand forecast.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Statsmodels
- Scikit-learn

## Workflow
1. Load and preprocess the dataset.
2. Visualize and decompose the time series.
3. Test stationarity.
4. Split the data into training and testing sets.
5. Fit and evaluate an ARIMA model.
6. Forecast future demand and export the results to CSV.

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload a CSV dataset containing a date column and a demand or numerical target column.
3. Run the notebook cells in order.
4. Review the evaluation metrics and forecast visualizations.

## Output
- Time series visualizations
- Trend and seasonality decomposition
- ARIMA model evaluation
- 30-day demand forecast



