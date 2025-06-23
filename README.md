# U.S. Consumption Forecasting with Time Series

This project uses quarterly U.S. economic data (1970–2016) to forecast personal consumption.  
The model combines regression and ARIMA errors to account for both macroeconomic predictors and temporal dependence.

### Summary
- **Tools**: R, forecast, fpp2
- **Model**: Regression with ARIMA(3,1,0)(1,0,0)[4]
- **Forecast period**: 2015 Q1 – 2016 Q3
- **Performance**: MAPE = 10.5%, RMSE = 0.097

### Files
- `Final-Project---Can-Guvener.pdf`: Full report
- `forecast_consumption.R`: Main R script
