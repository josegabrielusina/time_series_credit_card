# Time Series Analysis of Credit Usage in Mexico

**Author:** José Gabriel Usiña Mogro  
**Date:** September 2022

## Introduction
Time series analysis is utilized to analyze the dynamic changes in a variable over time. This analysis relies on time series data, which is a sequence of data collected over a period.

## Background
The number of households in Mexico is projected to increase by 16.9% by 2040. This growth is accompanied by a significant increase in household credit over the last six months.

## Description of the Problem Situation
Financiera Ma, a financial company in Mexico, faces lower-than-expected credit card usage. A comparison with countries like Argentina and Brazil reveals significant differences.

## Data and Methodology
- The data on credit card usage, inflation rate, GDP growth, unemployment, and consumer confidence is imported and cleaned.
- Time series analysis is conducted using various statistical techniques and models.

## Time Series Regression Analysis
Three models are developed:
1. ARMA (1,1) Model
2. ARIMA (1,1,1) Model
3. ARIMA (1,2,1) Model

### Model Evaluation
- Diagnostic tests are performed to assess the accuracy and validity of each model.
- ARIMA (1,2,1) emerges as the most accurate model due to its stationary residuals and lower AIC value.

### Forecasting
The ARIMA (1,2,1) model is used to forecast credit to households for the next five periods.

## VAR Model
A Vector Autoregression (VAR) model is developed to understand the relationship between credit to households and other economic indicators.

### Model Selection
- Lag selection suggests a lag of 5 periods for the VAR model.
- The VAR model reveals significant relationships between credit to households, GDP growth, unemployment, and consumer confidence.

### Forecasting
The VAR model is utilized to forecast credit to households for the next five periods.

# Conclusions and Recommendations
- The analysis indicates a growth trend in credit to households.
- Recommendations include focusing marketing efforts on employed individuals, leveraging GDP growth, and considering the constant value of 184.81 for financial estimations.

# References
- Euromonitor International. (2022, July). Households: Mexico: Country Report. Passport.
- TheGlobalEconomy.com. (n.d.). Mexico Household credit, billion currency units, June, 2022 - data, chart.
- Tableau. (n.d.). Time Series Analysis: Definition, Types, Techniques, and When It’s Used.
