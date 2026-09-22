# Predictive Analytics Using Historical Data
This project forecasts monthly Superstore sales using SARIMAX time-series forecasting.

## Workflow
- Data preprocessing and monthly aggregation
- 80/20 chronological train-test split
- SARIMAX forecasting
- MAE, RMSE, MAPE and R² evaluation
- 12-month future forecast
- 95% confidence interval
- Model serialization using Joblib

## Model
SARIMAX(1,1,1) × (1,1,1,12)

## Evaluation Metrics
- MAE: 13,141.30
- RMSE: 15,846.78
- MAPE: 21.28%
- R²: 0.5577

## Files
- `future_sales_forecast.csv` — 12-month forecast
- `model_metrics.csv` — evaluation metrics
- `monthly_sales.csv` — monthly historical sales
- `actual_vs_predicted.png` — model evaluation chart
- `future_sales_forecast.png` — forecast chart
- `sarimax_sales_model.pkl` — compressed serialized SARIMAX model
