# Spare Parts Inventory Optimization Using Time Series Forecasting

Managing spare parts inventory across service centers to meet fluctuating market demands can be a challenging task. Despite considerable investment in inventory, maintaining an adequate supply of parts often remains a pain point. This project addresses the problem through the application of time series forecasting techniques.

## Project Objective

The primary goal of this project is to enhance inventory management by accurately forecasting the demand for spare parts. By doing so, it aims to strike a balance between minimizing costs and maximizing availability, leading to improved service efficiency and customer experience.

## Repository Structure

- **[Setup](#setup)**: Installation of required libraries and tools.
- **[Data Loading](#data-loading)**: Importing the dataset for analysis.
- **[Initial Exploration](#initial-exploration)**: Performing exploratory data analysis (EDA) to get a basic understanding of the dataset.
- **[Data Cleaning](#data-cleaning)**: Preparing the data for analysis by addressing inconsistencies.
- **[Deep Dive into Data](#deep-dive-into-data)**: Analyzing patterns and uncovering insights through advanced EDA.
- **[Time Series Techniques](#time-series-techniques)**: Exploring trends, seasonality, and other time series components.
- **[Forecasting Models](#forecasting-models)**: Using predictive models to estimate future spare parts demand.
- **[Performance Metrics](#performance-metrics)**: Evaluating the effectiveness of the models.
- **[Multivariate Insights](#multivariate-insights)**: Enhancing predictions by including additional relevant variables in the SARIMAX model.

## Key Features in the Dataset

The dataset includes the following attributes, which serve as the foundation for analysis and forecasting:
- `invoice_date`
- `job_card_date`
- `business_partner_name`
- `vehicle_no`
- `vehicle_model`
- `current_km_reading`
- `invoice_line_text`

## Models Implemented

To tackle the demand forecasting challenge, the following models were utilized:
- **Autoregression (AR)**
- **Moving Average (MA)**
- **Exponentially Weighted Moving Average (EWMA)**
- **Holt-Winters Exponential Smoothing**
- **Seasonal ARIMA (SARIMA)**
- **SARIMAX with Exogenous Variables**

## Evaluation Criteria

Model performance was measured using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**

## Summary

This project demonstrates how time series forecasting can revolutionize inventory management by enabling data-driven decision-making. With precise demand forecasts, service centers can streamline inventory levels, reduce operational costs, and consistently meet customer needs.
