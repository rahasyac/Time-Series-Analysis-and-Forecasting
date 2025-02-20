# Time Series Analysis and Forecasting of the 10-Year Treasury Yield

This project analyzes historical trends in the **10-Year Treasury Yield**, a key economic indicator, and forecasts its future values using **ARIMA** and **SARIMA** models. It provides valuable insights for financial markets, investors, and policymakers.

## Objectives

- Analyze trends in the **10-Year Treasury Yield** to identify key patterns and anomalies.
- Forecast future interest rates using the **ARIMA** model for better market planning and risk management.
- Evaluate forecast performance using **MAE**, **RMSE**, and **MAPE** for model accuracy.
- Provide actionable insights to guide decision-making in financial markets and economic policy.

## Dataset

- **Source**: FRED® Economic Data
- **Variable**: Monthly data of the **10-Year Treasury Yield**
- **Time Period**: January 2000 to January 2025

### Data Description:
The dataset includes monthly data for the **10-Year Treasury Yield** (GS10). The data is used to conduct time series analysis and forecast future trends.

## Methodology

1. **Data Preprocessing**: The data is cleaned by handling missing values, formatting timestamps, and addressing anomalies.
2. **Trend Analysis**: Statistical methods are applied to identify patterns, including seasonal, cyclical, and long-term trends.
3. **Modeling**: The **ARIMA** and **SARIMA** models are used for forecasting the yield over the next 12 months.
4. **Model Evaluation**: The models are evaluated based on **MAE**, **RMSE**, and **MAPE**. Residual diagnostics are also conducted to assess model fit.

## Models Used

1. **ARIMA (Auto-Regressive Integrated Moving Average)**: Used to forecast future values based on the differences between values and past observations.
2. **SARIMA (Seasonal ARIMA)**: An extension of ARIMA, which accounts for seasonality in time series data.
3. **Holt-Winters Exponential Smoothing**: A model that considers trends and seasonal patterns in time series data for forecasting.

## Model Evaluation

For each of these models, we evaluated the forecast accuracy using:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **MAPE (Mean Absolute Percentage Error)**

### Results:
- **ARIMA MAE**: 0.2583
- **SARIMA MAE**: 0.2310
- **Holt-Winters MAE**: 0.2550

The **SARIMA** model performed slightly better in terms of accuracy, with lower MAE and RMSE values.

## Strategic Implications

- **Forecasting Trends**: The model suggests that the yield will stabilize or increase moderately in the next 12 months.
- **Impact on Markets**: The 10-year yield is a key indicator for bond markets and borrowing costs.
- **Economic Policy**: Policymakers should monitor treasury yields as they serve as an important signal of economic conditions and future inflation expectations.

## Future Improvements

- **Incorporating SARIMA**: Add seasonal components to the model to account for fiscal policies and recurring events.
- **Machine Learning Models**: Explore LSTM networks for better handling of non-linear relationships.
- **Macroeconomic Indicators**: Analyze other variables like inflation rates and GDP to improve model accuracy.

## Installation & Requirements

To run this project locally, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/10-Year-Treasury-Yield-Forecasting.git
cd 10-Year-Treasury-Yield-Forecasting
pip install -r requirements.txt

