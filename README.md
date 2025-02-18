# Real Estate Financing Patterns Analysis 📊
![R](https://img.shields.io/badge/R-4.1.0-blue)
![FRED](https://img.shields.io/badge/Data-FRED-green)
![Time Series](https://img.shields.io/badge/Analysis-Time%20Series-orange)

## 📌 Overview
A time series analysis project examining the relationship between residential real estate loans and mortgage rates using FRED data.

## 🎯 Project Goals
- Analyze trends in residential real estate financing
- Model the relationship between loan volumes and interest rates
- Forecast future patterns in real estate lending
- Provide insights for lending strategy development

## 📊 Data Analysis
We analyze two key time series:
- Residential Real Estate Loans from Commercial Banks
- 30-Year Fixed Rate Mortgage Average

The analysis includes:
- Time series decomposition
- Correlation analysis
- Stationarity testing
- Advanced forecasting models

## 🛠 Models Implemented
**RegARIMA Model**
- Combined regression with ARIMA errors
- Incorporates mortgage rates as external regressor
- MAE: 6.87518
- Final forecast: 2574.019

**VAR Model**
- Vector Autoregression approach
- Simultaneous modeling of both series
- MAE: 13.68
- Final forecast: 2573.884

## 📈 Results
The RegARIMA model outperformed the VAR model in terms of:
- Lower Mean Absolute Error
- Better forecast stability
- More reliable cross-validation results

## 💡 Applications
- Bank lending strategy optimization
- Risk assessment
- Market trend analysis
- Property pricing strategy development

## 🔧 Tech Stack
- R Statistical Software
- FRED Economic Data API
- Time Series Analysis Packages
  - forecast
  - vars
  - fpp3
  - tidyverse

## 👤 Author
**SREE LEKSHMI PRASANNAN**
- Time Series Analysis
- Economic Data Modeling
- Financial Forecasting




---
*This project is part of an advanced time series analysis study focusing on real estate financial patterns.*
