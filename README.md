# 🏠 Energy Consumption Forecasting in South Carolina

## 📌 Overview

This project was developed for **IST 687 - Introduction to Data Science** to predict residential energy consumption in South Carolina during the peak summer month of July. By leveraging machine learning models and detailed datasets on weather, home characteristics, and energy usage, the project aims to help energy providers manage grid demand and promote energy conservation.

---

## 🎯 Objectives

- **Develop a Predictive Model** to forecast July energy consumption (heating and cooling) in residential homes.
- **Identify Key Drivers** of energy usage using structured datasets and environmental factors.
- **Deliver Visual Insights** through an interactive Shiny application.

---

## 🗃️ Data Sources

Three main datasets were used:

1. **Static House Data**  
   Includes home attributes: square footage, number of bedrooms, HVAC type & efficiency, and county location.

2. **Energy Usage Data**  
   Hourly consumption of electricity, natural gas, propane, and usage for heating and cooling.

3. **Weather Data**  
   Hourly temperature, humidity, wind speed/direction across South Carolina counties.

---

## 🧪 Methodology

- **Data Cleaning & Integration**: Merged and aligned all datasets by building ID and timestamp.
- **Exploratory Data Analysis (EDA)**:
  - Trends in square footage, HVAC systems
  - Energy consumption over time
  - Temperature effects on heating/cooling
- **Predictive Modeling**:
  - Linear Regression (baseline)
  - XGBoost (advanced model)
- **Deployment**: A Shiny app to visualize predictions vs. actual energy use.

---

## 🧠 Key Insights

- Cooling energy consumption **increases sharply** with temperature, peaking in July.
- HVAC efficiency, number of occupants, and square footage are strong predictors.
- XGBoost achieved better performance than Linear Regression:
  - **Cooling R²:** 0.69
  - **Heating R²:** 0.66

---

## 📊 Visualization Tool

The **Shiny App** enables:
- Visualization of **actual vs predicted** heating and cooling energy.
- Interactive **filtering by date** for in-depth analysis during July.

---

## ✅ Recommendations

- **Incentivize energy-efficient technologies** (heat pumps, insulation).
- **Adopt smart home solutions** for automatic energy adjustments.
- **Implement progressive pricing** to encourage reduced consumption.
- **Educate high-usage households** about conservation benefits.

---

## 📌 Conclusion

This project delivers a powerful decision-making tool for energy providers, offering predictive insights and strategies to avoid grid overload during peak summer months. With the integration of smart tech, targeted incentives, and robust forecasting, this framework sets a solid foundation for sustainable energy management.

---

---

## 🛠️ Technologies Used

- R (tidyverse, ggplot2, xgboost, shiny)
- RStudio
- Git/GitHub
- Data Visualization
- Machine Learning

---



