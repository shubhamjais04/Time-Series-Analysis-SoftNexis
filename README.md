# Task 3: Time Series Analysis

**Internship:** Soft Nexis Technology
**Intern Name:** Shubham Jaiswal
**Intern ID:** SN1001074
**Domain:** Data Science & Machine Learning Using Python

---

# 📈 Time Series Analysis & Forecasting

A complete time series analysis and forecasting project on the classic Air Passengers dataset, covering trend identification, seasonality decomposition, and future forecasting using the ARIMA model.

---

## 📌 Project Overview

Time series data has unique patterns that standard ML models can't capture directly. This project demonstrates a structured approach to analyzing temporal data — decomposing it into trend, seasonality, and residual components, then building an ARIMA model to forecast future values with low error.

---

## ✨ What's Covered

- 📥 Data Loading & Inspection — Shape, data types, missing value checks
- 📊 Raw Time Series Visualization — Understanding the overall pattern
- 📆 Quarterly Resampling — Observing broader seasonal trends
- 🔬 Time Series Decomposition — Trend, Seasonality, and Residual separation
- 📉 Moving Averages — 6-month and 12-month smoothing
- 🤖 ARIMA Modeling — Forecasting last 12 months of passenger data
- 📐 Model Evaluation — RMSE scoring

---

## 📊 Dataset

- **Source:** Classic Air Passengers Dataset
- **Period:** 1949 – 1960
- **Records:** 144 monthly observations
- **Target:** Monthly airline passenger counts

---

## 🏆 Results

| Metric | Value |
|--------|-------|
| Model | ARIMA(2,1,1) |
| RMSE | 21.17 |
| Trend | Clear upward growth from 1949–1960 |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📁 Project Structure

```
Time-Series-Analysis-SoftNexis/
├── Task2_Time_Series_Analysis.ipynb    # Main analysis notebook
├── dataset/
│   ├── airline-passengers.csv          # Raw dataset
│   └── airline_passengers_final.csv    # Processed dataset
├── plots/
│   ├── plot1_raw_series.png            # Raw time series plot
│   ├── plot2_quarterly.png             # Quarterly resampled plot
│   ├── plot3_decomposition.png         # Decomposition plot
│   ├── plot4_moving_averages.png       # Moving averages plot
│   └── plot5_forecast.png             # ARIMA forecast plot
└── README.md                           # Project documentation
```

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/shubhamjais04/Time-Series-Analysis-SoftNexis.git
cd Time-Series-Analysis-SoftNexis
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib statsmodels scikit-learn jupyter
```

**3. Open the notebook**
```bash
jupyter notebook Task2_Time_Series_Analysis.ipynb
```

**4. Run all cells in order**

---

## 👨‍💻 Author

**Shubham Jaiswal**
*Time series analyst | Extracting patterns from temporal data to forecast what comes next*

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubhjais04)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shubhamjais04)
