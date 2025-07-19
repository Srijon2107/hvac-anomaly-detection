# HVAC Anomaly Detection using Time Series Forecasting

This project focuses on detecting anomalies in HVAC (Heating, Ventilation, and Air Conditioning) data using time series analysis with Facebook Prophet. The goal is to identify unexpected spikes or drops in energy consumption, which could indicate equipment faults, energy inefficiencies, or external interferences.

## 🚀 Project Overview

- **Dataset**: Energy consumption logs from HVAC systems over time.
- **Objective**: Detect anomalies by modeling the normal behavior of the system.
- **Approach**: 
  - Exploratory Data Analysis (EDA)
  - Time series forecasting using Prophet
  - Anomaly detection based on residuals (forecast vs. actual)
  - Visualizing anomalies


## 🧠 Key Concepts Used

- Time series decomposition
- Seasonality and trend detection
- Forecast confidence intervals
- Residual analysis for anomaly detection

## 🛠️ Tech Stack

- Python
- Prophet
- Pandas, Matplotlib, Seaborn
- Jupyter Notebook

## 📈 Results

The model forecasts expected HVAC energy consumption and flags data points that significantly deviate from the prediction intervals as anomalies. These insights can help facilities teams monitor operational efficiency and prevent breakdowns.

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/Srijon2107/hvac-anomaly-detection.git
cd hvac-anomaly-detection

# Install dependencies
pip install -r requirements.txt



