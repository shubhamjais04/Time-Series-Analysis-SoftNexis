# Task 3: Time Series Analysis

**Internship:** Soft Nexis Technology
**Intern Name:** Shubham Jaiswal
**Intern ID:** SN1001074
**Domain:** Data Science & Machine Learning Using Python

---

## Objective
Analyze the Air Passengers dataset (1949-1960) to identify trends, seasonality and forecast future passenger counts using the ARIMA model.

---

## Steps Performed

1. **Loaded and inspected** the dataset — checked shape, data types and missing values
2. **Plotted raw time series** to visually understand the overall pattern
3. **Resampled to quarterly** frequency to observe broader trends
4. **Decomposed** the time series into Trend, Seasonality and Residual components
5. **Calculated Moving Averages** — 6 month and 12 month to smooth fluctuations
6. **Built ARIMA model** to forecast the last 12 months of passenger data
7. **Evaluated the model** using RMSE score

---

## Results
- Clear upward trend observed from 1949 to 1960
- Strong seasonality — peaks every July, lowest every February
- ARIMA model successfully forecasted passenger counts with low error

---

## Folder Structure
```
Task3_Time_Series/
├── Task3_Time_Series_Analysis.ipynb
├── README.md
├── dataset/
│   ├── airline-passengers.csv
│   └── airline_passengers_final.csv
└── plots/
    ├── plot1_raw_series.png
    ├── plot2_quarterly.png
    ├── plot3_decomposition.png
    ├── plot4_moving_averages.png
    └── plot5_forecast.png
```

---

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn