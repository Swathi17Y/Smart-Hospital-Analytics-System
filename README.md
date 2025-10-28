
# 🏥 Smart Hospital Analytics System  
**A Healthcare Data Analytics Project using Python, Machine Learning & Power BI**

---

## 🎯 Objective
To build a data-driven decision support system for hospitals that:
- Predicts **patient no-shows**
- Forecasts **bed & ICU utilization**
- Detects **disease outbreak trends** using weather data

This project integrates predictive modeling and business intelligence to optimize hospital operations and improve patient care.

---

## 🧠 Project Overview

| Module | Description | Tools Used |
|--------|--------------|------------|
| 🩺 Patient No-Show Prediction | Predicts which patients are likely to skip appointments | Python (Logistic Regression), Power BI |
| 🏥 Resource Forecasting | Forecasts daily hospital & ICU bed utilization | SARIMAX (Statsmodels) |
| 🌡️ Disease Outbreak Detection | Predicts case surges using rainfall, temperature, humidity | Random Forest Regressor |
| 📊 Dashboard | Interactive Power BI dashboard with KPIs & trends | Power BI, DAX, Plotly |

---

## ⚙️ Tech Stack
**Languages:** Python  
**Libraries:** pandas, numpy, scikit-learn, statsmodels, matplotlib  
**BI Tool:** Power BI  
**Dashboard KPIs (DAX):**
- `No-Show % = AVERAGE(noshow_analysis[target]) * 100`
- `Avg ICU Utilization % = AVERAGE(resource_daily[util_icu]) * 100`
- `Avg Bed Utilization % = AVERAGE(resource_daily[util_beds]) * 100`
- `Avg Daily Cases = AVERAGE(cases_weather_daily[cases])`

---

## 🧩 Folder Structure

