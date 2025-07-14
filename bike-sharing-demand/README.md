# Bike Sharing Demand Forecasting & Optimization Dashboard

### Power BI | Predictive & Prescriptive Analytics | University of Niagara Falls

> **Author:** Rosario Torres  
> **Tools Used:** Power BI, DAX, Python (Random Forest), Data Transformation  
---

## Overview

This project analyzes a two-year daily bike rental dataset to forecast demand and guide operational planning. Through interactive **Power BI dashboards**, I applied both **predictive** and **prescriptive analytics** to answer the key business question:

> *“How many bikes should be allocated each season to meet demand while minimizing excess inventory?”*

This study simulates a real-world decision-making scenario relevant to companies in **transportation, logistics, and sharing economy platforms**, where **data-driven allocation planning** is essential for cost control and customer satisfaction.

---

## Objectives

- Analyze rental trends across **season**, **weather**, **temperature**, and **day type**
- Build a **Random Forest regression model** to forecast daily bike rental demand
- Generate **prescriptive recommendations** for optimal seasonal bike allocation
- Create a **multi-dashboard Power BI report** for interactive decision support

---

## Key Dashboards & Features

| Dashboard | Purpose |
|----------|---------|
| **Exploratory Dashboard** | Discover patterns in rentals across time, weather, season, and working day |
| **Predictive Dashboard** | Visualize and compare rental forecasts using Random Forest and baseline models |
| **Prescriptive Dashboard** | Recommend optimal bike counts per season based on forecasted demand |
| **Feature Importance** | Rank features using correlation and model-derived importance scores |
| **Interactive Slicers** | Filter results by season, holiday, weekday, and weather condition |

---

## Core Insights

- **Temperature** is the strongest predictor of bike rentals (correlation: 0.63)
- **Rentals drop by 60%** on light snow or rainy days
- **Weekdays** (commute demand) outperform weekends
- **Summer** has the highest average rentals (~5,630/day); **Winter** the lowest (~2,622/day)

---

## Model Performance (Random Forest)

- **R² Score:** 0.64  
- **RMSE:** 1173  
- Outperformed Linear Regression and Untuned XGBoost in capturing nonlinear patterns  
- **Top Predictors:** Temperature, Season, Holiday, Working Day, Wind Speed

---

## Prescriptive Recommendations

| Season | Avg Rentals | Recommended Bikes |
|--------|-------------|-------------------|
| Summer | ~5,630      | 5,644             |
| Spring | ~4,215      | 4,208             |
| Fall   | ~4,169      | 4,172             |
| Winter | ~2,622      | 1,939             |

*Recommendations are rounded based on mean daily demand and model forecast.*

---

## Relevance to Industry

This project mirrors the type of analysis performed by:
- Bike-sharing startups planning fleet size and station rebalancing
- Logistics firms forecasting seasonal delivery volumes
- Hospitality or recreation services aligning staffing/resources with seasonal demand
- Any company applying **data-driven forecasting** and **resource optimization**

---

## Skills Demonstrated

- ✅ **Data wrangling** using Power BI’s query editor and transformations
- ✅ **Feature engineering** (e.g., converting temperature scales, date parsing)
- ✅ **Predictive modeling** using **Python’s Random Forest** in Jupyter
- ✅ **DAX measures** for dynamic KPIs and filtering
- ✅ **Dashboard design** with clear narrative flow and business use case
- ✅ **Interpretation of model outputs** and translating them into **operational recommendations**


---

## Next Steps

- Add **real-time weather API** to update forecasts dynamically
- Incorporate **time series models** (Prophet, ARIMA)
- Expand to **city-level demand analysis** using geospatial data
- Publish online using **Power BI Service** or **Streamlit dashboard**

---






