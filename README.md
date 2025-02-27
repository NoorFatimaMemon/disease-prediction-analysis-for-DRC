# Predictive Analysis of Cholera Disease Outbreaks

This project uses time series forecasting methods (Prophet, ARIMA, SARIMAX) to predict disease cases and deaths in the Democratic Republic of Congo for 2024. Based on historical data, the goal is to forecast specific disease-related metrics in children and the general population.

## Project Overview

The dataset contains information on:
- Disease cases and deaths by age group
- Provincial and health zone data
- Weekly records spanning multiple years

The task is to drop the data for the year 2021, use time series models to predict specific disease metrics for 2024, and calculate additional values like total cases, total deaths, lethality, and attack rate.

## Key Features:
- **Data Preprocessing:** Removal of 2021 data
- **Forecasting Models:** Use of Prophet, ARIMA, and SARIMAX for forecasting cases and deaths for the year 2024
- **Metrics Calculation:** Calculation of total cases, total deaths, lethality, and attack rate based on model predictions
