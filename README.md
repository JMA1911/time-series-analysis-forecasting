# Time Series Analysis and Forecasting

## MSc Financial Mathematics – Applied Statistics and Probability Project (University of Leeds)

This repository contains the R implementation and report for my MSc Financial Mathematics Applied Statistics and Probability Project completed at the University of Leeds.

The project develops and compares multiple statistical time series models for forecasting financial markets using DAX index data. Model selection is performed through autocorrelation analysis, stationarity testing and statistical diagnostics before comparing forecasting performance against a multivariate VAR model.

---

## Methods Implemented

- Autocorrelation (ACF/PACF) analysis
- Augmented Dickey-Fuller stationarity testing
- AR(1), MA(1) and ARIMA(1,1,1) models
- Residual diagnostics
- Ljung-Box tests
- AIC/BIC model selection
- Vector Autoregressive (VAR) modelling
- Forecast accuracy evaluation using RMSE and MAE

---

## Tools

- R
- forecast
- vars
- tseries
- urca
- ggplot2

---

## Key Results

- Selected ARIMA(1,1,1) as the best univariate model using AIC, BIC and residual diagnostics.
- Developed a VAR(2) model using multiple stock indices to improve forecasting performance.
- Demonstrated lower RMSE and MAE for the VAR model compared with the ARIMA benchmark.
- Produced a fully reproducible forecasting workflow and statistical analysis in R.

---

## Repository Contents

- `time_series_analysis_forecasting.Rmd` – Complete modelling and analysis code.
- `Time Series Analysis and Forecasting Report.pdf` – Coursework report.

---

# Author

**Jack Adams**

MSc Financial Mathematics (Distinction)

University of Leeds

LinkedIn: https://www.linkedin.com/in/jackmadams
