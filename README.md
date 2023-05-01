# Time Series Forecasting of Monthly Average Temperature in Lagos

## Overview

This project uses time series analysis to forecast the monthly average temperature in Lagos, Nigeria from 1900 to 2012. Lagos is considered one of the most vulnerable places on Earth to climate change consequences, making it an important case study for analyzing the effects of rising temperatures. The main goal of this project is to show that the average temperature in Lagos has risen significantly over the years and to provide a reliable predictor for future temperature trends.

## Dataset

The dataset used in this project contains 1356 monthly observations of average temperature in Lagos, represented in Celsius degrees. The data is transformed into a time series object for further analysis, with train data ranging from 1900 to 2012 and test data for 2012 only. The dataset does not contain any outliers.

## Analysis

The data is analyzed for trend, seasonality, and stationarity using various techniques, including ACF and PACF plots, ggseasonplot, and the Augmented Dickey Fuller Test and Kwiatkowski-Phillips-Schmidt-Shin Test for stationarity. The data is found to be non-stationary due to the presence of trend and seasonality, which are then removed using seasonal differencing and detrending.

Different models are then built and evaluated for their adequacy, with two models (MODEL 4 and MODEL 5) being selected for forecasting. Forecasting is done for the next 24 months, and the accuracy of the forecasts is evaluated using RMSE, MAE, MAPE, and MASE.

## Results

The project shows that the temperature in Lagos has significantly increased over the years, and that the rising trend is likely to continue. The selected models provide accurate forecasts for the next 24 months, with MODEL 5 performing slightly better than MODEL 4.

The results of this project have important implications for combating global warming and raising awareness about the need to reduce greenhouse gas emissions.


## Dependencies

The project was developed using R programming language and requires the following packages:

- forecast
- ggplot2
- TSA
- astsa
- xts
- zoo
- Quandl
- tseries

## Authors

Agata Dratwa
