# Forecasting Forex Exchange Rates Using Time Series Models: A Case Study of USD/KSH and USD/UGX
![Pic1](https://github.com/user-attachments/assets/7a5e665d-8e18-44fe-a523-cd4c1ec3e816)

## Objective

The objective of this project is to develop a predictive model for forecasting future exchange rates of USD/KSH (US Dollar to Kenyan Shilling) and USD/UGX (US Dollar to Ugandan Shilling). 

## Background and Motivation

Foreign exchange rates play a crucial role in global financial markets. For foreign expatriates, knowing the optimal times to exchange USD to local currencies can lead to significant financial benefits. In addition accurate forecasting of these rates can benefit traders, investors, and policymakers.

## Data Source: 
- ALPHA VANTAGE: Alpha Vantage provides realtime and historical financial market data through a set of powerful and developer-friendly data APIs and spreadsheets. https://www.alphavantage.co/

## Methodology

### Data Collection:
The data will be extracted using an API from https://www.alphavantage.co/support/#api-key

### Data Preprocessing
- Clean and handle missing values.
- Perform feature engineering 
- Normalize the data for consistent scaling.
  
### Exploratory Data Analysis (EDA)
- Visualize the time series data and identify trends and seasonality.
- Calculate statistical properties such as mean, variance, and autocorrelation.
  
### Model Development
- ARIMA (Auto Regressive Integrated Moving Average)
- SARIMA
- LSTM (Long Short-Term Memory)
  
### Model Evaluation
- Split data into training and testing sets. 
- Use cross-validation to tune model hyperparameters.
- Evaluate models using metrics like RMSE and MAE
  
### Tools and Technologies
- Programming Language: Python
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, Plotly, alpha_vantage
- Environment: Jupyter Notebooks

### Expected Outputs
- A comparison of ARIMA and LSTM models for forex rate prediction.
- Insights into the optimal times for foreign expatriates to exchange USD to local currencies and identify the trends and patterns in the exchange rates.
- As an addition, deployed model providing real-time forex predictions with a user-friendly interface.

