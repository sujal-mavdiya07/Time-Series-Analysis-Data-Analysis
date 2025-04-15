# Time-Series-Analysis-Data-Analysis

# 🌡️ Time Series Analysis of Global Temperature Data

This project focused on analyzing the Global Surface Temperature Time Series using historical data provided by NASA. The goal is to explore patterns, trends, and seasonality in the data, and apply statistical methods to gain insights into how global temperatures have evolved over time.

## 📊 Project Overview

This time series analysis project involves:

- Cleaning and preprocessing the raw temperature data
- Visualizing long-term temperature trends
- Detecting seasonality and local patterns
- Applying statistical tests to check stationarity
- Fitting regression models to observe trends
- Performing autocorrelation and decomposition analysis

## 📁 Dataset

- **Source**: [NASA GISTEMP](https://data.giss.nasa.gov/gistemp/)
- **Data Used**: Monthly and annual global surface temperature anomalies

## 🔍 Analysis Techniques

- **Rolling Mean & Smoothing**: Used to highlight long-term trends and reduce noise
- **Linear & Polynomial Regression**: For trend estimation over time
- **Detrending**: Differencing method used to remove long-term trends
- **Deseasonalizing**: To isolate the seasonality component
- **ADF & KPSS Tests**: To evaluate the stationarity of the time series
- **Autocorrelation**: ACF & PACF plots to analyze lag relationships
- **Matrix-Based Local Trend Estimation**: An experimental approach using row/column averaging

## 📈 Visualizations

The repository includes multiple graphs that depict:

- Temperature anomaly time series
- Rolling averages (e.g., 12-month window)
- Linear and polynomial regression fit lines
- Seasonal decomposition (trend, seasonality, residuals)
- Detrended and deseasonalized series
- ACF and PACF plots for autocorrelation insight

## 🛠️ Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for plotting
  - `statsmodels` for time series modeling and statistical tests
  - `scikit-learn` for regression modeling

## 📌 Google Colab Link
 https://colab.research.google.com/drive/1iX2NbsVlBbkg7DyELiU
 B8NhygZq3raCR?usp=sharing#scrollTo=SOW6xXupplxS.

