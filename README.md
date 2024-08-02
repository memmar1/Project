# Forecasting Forex Exchange Rates Using Time Series Models: A Case Study of USD/KSH and USD/UGX

## Objective

The objective of this project is to develop a predictive model for forecasting future exchange rates of USD/KSH (US Dollar to Kenyan Shilling) and USD/UGX (US Dollar to Ugandan Shilling). 

## Background and Motivation

Foreign exchange rates play a crucial role in global financial markets. For foreign expatriates, knowing the optimal times to exchange USD to local currencies can lead to significant financial benefits. In addition accurate forecasting of these rates can benefit traders, investors, and policymakers.

## Data Source: 
- OANDA

## Methodology

### Data Collection:
Use OANDA API 

### Data Preprocessing
- Clean and handle missing values.
- Perform feature engineering 
- Normalize the data for consistent scaling.
  
### Exploratory Data Analysis (EDA)
- Visualize the time series data and identify trends and seasonality.
- Calculate statistical properties such as mean, variance, and autocorrelation.
  
### Model Development
- ARIMA (Auto Regressive Integrated Moving Average)
- LSTM (Long Short-Term Memory)
  
### Model Evaluation
- Split data into training and testing sets. 
- Use cross-validation to tune model hyperparameters.
- Evaluate models using metrics like RMSE and MAE
  
### Tools and Technologies
- Programming Language: Python
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, Plotly
- Environment: Jupyter Notebooks

### Expected Outputs
- A comparison of ARIMA and LSTM models for forex rate prediction.
- Insights into the optimal times for foreign expatriates to exchange USD to local currencies and identify the trends and patterns in the exchange rates.
- As an addition, deployed model providing real-time forex predictions with a user-friendly interface.

