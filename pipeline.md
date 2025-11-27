# Multivariate Time Series Forecasting: Data Preparation & Feature Engineering

## 1. Data Preparation
- **Collect Data:** Gather all relevant time series and exogenous variables.
- **Handle Missing Values:** Impute or remove missing data points.
- **Resample/Align:** Ensure all series have the same frequency and timestamps.
- **Outlier Detection:** Identify and handle anomalies.
- **Scaling/Normalization:** Standardize features (e.g., MinMaxScaler, StandardScaler).

## 2. Feature Engineering
- **Lag Features:** Create lagged versions of each variable (e.g., t-1, t-2).
- **Rolling Statistics:** Compute rolling mean, std, min, max, etc.
- **Datetime Features:** Extract hour, day, month, weekday, seasonality indicators.
- **Interaction Features:** Combine variables to capture relationships.
- **Domain-Specific Features:** Add relevant external factors (e.g., holidays, weather).
- **Target Encoding:** For categorical variables, encode appropriately.

## 3. Final Steps
- **Train/Test Split:** Split data chronologically to avoid leakage.
- **Collinearity Check:** Remove highly correlated features if needed.
- **Feature Selection:** Use statistical tests or model-based selecti