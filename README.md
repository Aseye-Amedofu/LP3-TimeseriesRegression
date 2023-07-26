# Time Series Sales Forecasting using ARIMA

## Overview
This project aims to forecast sales for a supermarket chain using time series analysis with the ARIMA (AutoRegressive Integrated Moving Average) model. The dataset contains historical sales data along with additional features such as promotions, holidays, oil prices, and store information.

## Table of Contents
- [Project Overview](#overview)
- [Table of Contents](#table-of-contents)
- [Data Source](#data-source)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Stationarity Test](#stationarity-test)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [ARIMA Model Building](#arima-model-building)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)
- [References](#references)

## Data Source
The dataset used in this project includes the following files:
- Train dataset: Contains historical sales data with various features.
- Test dataset: Similar to the train dataset but without the 'sales' column.
- Holiday Events dataset: Includes information about holidays and events.
- Oil dataset: Contains historical oil prices.
- Stores dataset: Provides information about different supermarket stores.
- Transactions dataset: Includes the number of transactions for each store.

## Data Preprocessing
Data preprocessing involves handling missing values, converting date columns to datetime format, and merging relevant datasets. It also includes feature engineering to extract date components such as year, month, day, and day of the week.

## Exploratory Data Analysis (EDA)
EDA is performed to understand the distribution of sales, explore trends and seasonality in the data, and visualize relationships between variables.

## Stationarity Test
Before applying time series forecasting techniques, it is crucial to check for stationarity in the data. The Augmented Dickey-Fuller (ADF) test is used to test for stationarity.

## Hyperparameter Tuning
Hyperparameter tuning is performed to identify the best parameters (p, d, q) for the ARIMA model. Grid search or other optimization techniques can be used to find the optimal hyperparameters.

## ARIMA Model Building
The ARIMA model is built using the selected hyperparameters on the training dataset. It involves fitting the ARIMA model and making predictions on the test dataset.

## Model Evaluation
The performance of the ARIMA model is evaluated using various metrics such as RMSE (Root Mean Squared Error), MSE (Mean Squared Error), MAE (Mean Absolute Error), and RMSLE (Root Mean Squared Logarithmic Error).

## Conclusion
The final section provides a summary of the project's findings, including insights from the EDA, performance of the ARIMA model, and recommendations for further improvements.

## Dependencies
The following libraries are required to run the project:
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scikit-learn

## How to Run
1. Clone the repository to your local machine.
2. Install the required dependencies using pip or conda.
3. Run the Jupyter notebook or Python script sequentially to execute each step of the project.
