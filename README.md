# Retail Demand Forecasting with Time-Series Analysis

## Project Overview
This project analyzes a dataset of over 540,000 transactions from a UK-based non-store online retailer. The primary goal is to extract insights from the data and develop a time-series forecasting model to predict product demand one month in advance. The forecast can help optimize inventory management and streamline stock replenishment.

## Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **Transactions Period**: December 2010 – December 2011
- **Instances**: 541,909
- **Features**: 6 (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country)

The dataset includes key attributes such as transaction dates, product quantities, and customer locations, allowing for both demand forecasting and deeper insights into customer purchasing behavior.

## Project Steps
1. **Data Analysis and Exploration**  
   - Explored the dataset to understand the sales trends, popular products, and customer purchasing behavior.
   - Visualized data using graphs and charts to reveal patterns in demand, seasonality, and geographic trends.
   
2. **Data Preprocessing**
   - Cleaned and prepared the data by handling missing values, removing duplicates, and converting dates to time-series format.
   - Feature engineering to create new variables like monthly demand and customer segmentation.

3. **Demand Forecasting Model**
   - Built a time-series forecasting model to predict future demand using historical sales data.
   - Evaluated different models (ARIMA, Prophet, etc.) to select the one with the highest predictive accuracy.
   
4. **Model Evaluation**
   - Validated the model performance using metrics like RMSE and MAE.
   - Tested the model’s ability to forecast product demand one month ahead.
