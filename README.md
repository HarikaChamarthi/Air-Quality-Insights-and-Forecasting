# Air-Quality-Insights-and-Forecasting

Key libraries used:
-----------------------------------------------------------------------------

Pandas, NumPy — for data manipulation and numerical operations

Matplotlib, Seaborn, Plotly — for visualizations of air-quality trends and forecasts

scikit-learn — for machine-learning models (e.g., regression, classification)

statsmodels or Prophet — for time-series forecasting (if used)

Streamlit (optional) — for the interactive dashboard/web interface (if implemented)


📂 Dataset & Data Workflow
---------------------------------------------------------------------------------------------------

This project analyses and forecasts air-quality data using historical pollutant and meteorological measurements.

Data Source & Description

Data was collected for Indian cities (for example: New Delhi, Mumbai, etc.) spanning years 2015-2020 (or whatever your actual span is).

Pollutants include:

PM₂.₅ (fine particulate matter)

PM₁₀ (coarse particulate matter)

NO₂, SO₂, O₃, CO (other common pollutants)

Meteorological variables may include: temperature, humidity, wind-speed, rainfall (if used).

The dataset is formatted with a timestamp (e.g., hourly/daily) and pollutant concentrations.
