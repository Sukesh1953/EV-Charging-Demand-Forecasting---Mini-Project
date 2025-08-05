# EV-Charging-Demand-Forecasting---Mini-Project
# 🔋 EV Energy Load Forecasting with Machine Learning

This project showcases how machine learning can be used to forecast energy demand from electric vehicles (EVs) — an essential component for climate-tech companies like **Tether**, which aim to turn EVs into AI-coordinated grid-scale batteries.

---

## 📌 Project Objective

The goal is to predict the future energy load of EVs over time using historical consumption data. This can help:

- Optimize charging behavior
- Improve grid stability and balance
- Support scalable clean energy adoption

---

## 📊 Dataset

A mock dataset was generated with the following fields:

- `Date` – Daily timestamps
- `EV_Consumption_kWh` – Simulated daily energy consumed by EVs in kWh

> ⚠️ Replace this with real-world datasets to achieve production-grade results.

---

## 🔧 Tech Stack

- **Language**: Python
- **Libraries**:
  - pandas
  - matplotlib & seaborn (for visualization)
  - scikit-learn (for Linear Regression)
  - xgboost (for advanced modeling)

---

## 📈 Models Used

- **Linear Regression** – Baseline model to capture trends
- **XGBoost Regressor** – More powerful gradient boosting model for non-linear patterns

### ✅ Evaluation Metric:
- **RMSE (Root Mean Squared Error)**:  
  - Lower RMSE = Better predictive accuracy  
  - Achieved **~25 kWh**, indicating a relatively accurate forecast on mock data.

---

## 📉 Results

The models successfully learned patterns in the simulated EV energy consumption and generated forecasts for future dates.

- XGBoost outperformed Linear Regression in both accuracy and trend detection.
- Visualizations help identify peaks in demand, aiding smart charging decisions.

---

## 📌 Use Case for Climate-Tech Startups

This forecasting technique can be integrated with:
- Real-time charging station data
- Grid load balancing systems
- EV fleet management tools

Helping startups like **Tether**:
- Automate charging coordination
- Bid flexible loads on energy markets
- Maximize grid efficiency with clean energy sources

---

## 📁 Files

- `ev_load_forecasting.ipynb` – Main Jupyter Notebook
- `ev_consumption_data.csv` – Sample dataset (optional)
- `forecast_output.png` – Model visualization

---
   git clone https://github.com/yourusername/ev-load-forecasting.git
