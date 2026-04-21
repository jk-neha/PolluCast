# 🌫 PolluCast - Live Air Pollution Prediction System

PolluCast is a Machine Learning-based Air Quality Index (AQI) prediction system that uses real-time environmental data (pollutants + weather) to predict AQI levels and classify air quality into health categories.

---

## 🚀 Live Demo (After Deployment)

---

## 📌 Project Features

- 🌍 AQI prediction using ML models
- 🌲 Random Forest / Gradient Boosting models
- 📊 Feature engineering (lags, rolling averages)
- 🌫 CPCB-based AQI classification
- 🚨 Air quality category alerts
- 🌐 Flask REST API for real-time prediction
- ☁️ Deployable on Render

---

## 🧠 Machine Learning Models

- Random Forest Regressor
- Gradient Boosting Regressor

### Evaluation Metrics:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## 📥 Input Features

The API expects the following inputs:

- pm2_5
- pm10
- co
- no
- no2
- o3
- so2
- nh3
- temperature (°C)
- humidity (%)

---

## 📤 Output

```json
{
  "AQI": 128.45,
  "Category": "Moderate"
}
