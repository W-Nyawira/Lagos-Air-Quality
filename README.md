# 🌫️ Lagos Air Quality Time Series Analysis

This project analyzes PM2.5 air quality data collected in Lagos using time‑series analysis. It aims to explore trends, detect anomalies, and provide insight into pollution patterns over time.

---

## 🔍 Project Overview

- **Goal**: Understand how PM2.5 levels in Lagos fluctuate over time, detect abnormal pollution events, and explore relationships with meteorological factors.
- **Scope**: Data wrangling, visualization, time‑series modeling, and interpretation of air quality trends.

---

## 🗂️ Dataset & Sources

- **Source**: Low‑cost sensor data (e.g., P2 readings for PM2.5) collected from Lagos.   https://open.africa/it/dataset/sensorsafrica-airquality-archive-lagos
- **Data Format**: CSV or database extracts stored in `data/` (e.g. `lagos_pm25.csv`).
- Key columns include:
  - `timestamp` (in UTC, converted to Africa/Lagos)
  - `P2` (PM2.5 concentration)
  - Other variables (temperature, humidity, PM10)

---

## 🧪 Project Structure
---

## ⚙️ Data Wrangling & Processing

- Retrieve `P2` PM2.5 readings from sensor logs or CSV.
- Convert UTC timestamps to Africa/Lagos timezone :contentReference[oaicite:1]{index=1}.
- Remove outliers 
- Resample time-series data (e.g., hourly aggregation).
- Handle missing values with forward-fill methodology

---

## 📊 Exploratory Analysis & Modeling

- Visualize time-series trends and seasonal patterns.
- Apply time-series decomposition to reveal trend, seasonality, and residuals.
- Detect anomalies or pollution spikes using rolling-based thresholds or residual analysis.

---

## 📈 Key Findings & Insights

- Visual charts showing peaks and low periods in PM2.5 levels.
- Seasonal behavior (e.g., high pollution during dry season).
- Anomaly detection results highlighting pollution events.
