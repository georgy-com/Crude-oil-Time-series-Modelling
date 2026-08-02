# 🇳🇬 Forecasting Nigerian Crude Oil Production and Exports Using Time Series Analysis (2006–2023)

## Project Overview

This project applies **time series analysis and forecasting techniques** to examine historical trends in Nigeria's crude oil sector from **2006 to 2023**. Using Python, the analysis explores monthly crude oil production, exports, and international oil prices, and develops forecasting models to predict future production levels.

The project demonstrates practical applications of data analysis, statistical modeling, visualization, and forecasting techniques that support data-driven decision-making in the energy sector.

## Objectives

- Analyze historical trends in Nigeria's crude oil production.
- Examine monthly crude oil export patterns.
- Explore international crude oil price movements.
- Identify long-term trends and seasonal patterns.
- Evaluate relationships between production, exports, and oil prices.
- Build an ARIMA time series forecasting model.
- Forecast crude oil production for the subsequent year.
- Provide economic insights relevant to Nigeria's petroleum industry.

## Dataset

The dataset contains **215 monthly observations** spanning **January 2006 to November 2023**, including:

- Year
- Month
- Crude Oil Price (USD/Barrel)
- Crude Oil Production (Million Barrels per Day)
- Crude Oil Exports (Million Barrels per Day)
- 
## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## Analysis Performed

- Data loading and preprocessing
- Date-time indexing
- Descriptive statistics
- Missing value analysis
- Correlation analysis
- Monthly production trend analysis
- Annual production analysis
- Annual export analysis
- Oil price trend analysis
- Rolling average analysis
- Seasonal decomposition
- Stationarity testing (ADF Test)
- ARIMA model development
- Model evaluation (MAE & RMSE)
- Forecast visualization

## Key Findings

- Nigeria's crude oil production experienced considerable fluctuations between 2006 and 2023.
- Crude oil exports closely followed production trends, indicating strong dependence on production capacity.
- International crude oil prices exhibited significant volatility due to global economic events.
- The production series was found to be non-stationary and required first-order differencing before modeling.
- The ARIMA(1,1,1) model produced satisfactory forecasting accuracy and projected relatively stable production levels in the forecast period.

## Model Performance

| Mean Absolute Error (MAE) | 0.1443 |
| Root Mean Squared Error (RMSE) | 0.1583 |

## Future Improvements

- Implement SARIMA and SARIMAX models.
- Compare ARIMA with Facebook Prophet and Holt-Winters forecasting.
- Extend forecasts to 2026.
- Build an interactive dashboard using Plotly or Power BI.
- Incorporate additional economic indicators such as exchange rates, inflation, and OPEC production quotas.

## Skills Demonstrated

- Time Series Analysis
- Forecasting
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Feature Engineering
- Python Programming
- Predictive Analytics
- Model Evaluation

## 👤 Author

**Nku George Ekong**

Aspiring Data Scientist | Data Analyst | Statistician | AI & ML Enthusiast

Passionate about applying data-driven solutions to solve real-world economic, business, and public policy challenges.

---

⭐ If you found this project useful, feel free to **star** the repository and connect with me on LinkedIn.
