Summary of ML Model :
Data Preparation

The dataset is loaded and inspected.
A threshold is set to identify high-consumption spare parts based on demand.
Time Series Forecasting using ARIMA

The ARIMA (AutoRegressive Integrated Moving Average) model is chosen for forecasting.
Model parameters (p, d, q) are set manually (or optimized using grid search).
The model is trained on historical data.
Forecasting

The model predicts demand for the next 6 months.
Predictions are stored and indexed by date.
Conclusion:
The ARIMA model is used to predict future demand for spare parts.
High-consumption parts are prioritized for forecasting.
Results help in inventory planning by providing demand trends.
Trend Observation:
The forecasted consumption values for Material 94172 show an increasing trend over time:
From 4.81 units in September 2016 to 8.15 units in February 2017.
This suggests a consistent rise in demand, which could indicate:
Seasonal demand patterns.
Growth in usage or consumption over time.
