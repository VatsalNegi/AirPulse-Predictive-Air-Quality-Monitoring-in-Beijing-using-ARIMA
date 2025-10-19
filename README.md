# AirPulse: Predictive Air Quality Monitoring in Beijing using ARIMA 🌆📈

**Description:**  
AirPulse predicts daily PM2.5 levels in Beijing using the ARIMA model. The project includes **data preprocessing, exploratory analysis, 30-day forecasting**, and an **interactive Plotly dashboard** highlighting extreme pollution days for actionable insights.

---

## Features
- Historical PM2.5 analysis (2010–2014)  
- Missing value handling & daily aggregation  
- ARIMA-based 30-day PM2.5 forecast  
- Interactive dashboard with actual vs forecasted values  
- Extreme pollution days highlighted (PM2.5 > 150 µg/m³)  
- KPI insights: average, max, min PM2.5  

---

## Technologies
- Python: `pandas`, `numpy`, `statsmodels`, `plotly`  
- ARIMA for time series forecasting  
- Plotly for interactive visualization  

---

## Repository Structure
AirPulse/
│
├─ data/
│ ├─ raw/ # Original dataset
│ └─ processed/ # Cleaned daily data, forecasted data, dashboard data
│
├─ notebooks/
│ ├─ 1_data_preprocessing.ipynb
│ ├─ 2_EDA_ARIMA_Modeling.ipynb
│ └─ 3_dashboard.ipynb
│
├─ scripts/ # Optional Python scripts for preprocessing and modeling
├─ README.md
└─ requirements.txt # Python dependencies

