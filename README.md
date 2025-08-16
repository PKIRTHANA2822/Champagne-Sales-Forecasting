# Project: 
- Champagne Sales Forecasting using Time Series Analysis
 ![1679119929671](https://github.com/user-attachments/assets/ca1a680c-717a-4e47-a007-f5873a2d2be2)
# Objective
- The objective of this project is to analyze and forecast monthly Champagne sales for Perrin Frères using time series modeling techniques. The goal is to identify sales trends, seasonal patterns, and forecast future demand to assist in inventory planning and business decision-making.
# Why We Use This Project
- Business Use Case: Wine and champagne businesses need to anticipate sales for production planning, supply chain management, and marketing strategies.
- Data Science Perspective: Time series modeling helps in understanding trend, seasonality, and stationarity in sales data.
- Practical Value: Improves decision-making by predicting future sales and reducing overstock/understock situations.
# Step-by-Step Approach
- Problem Understanding & Objective Setting
- Define the business goal (forecast champagne sales).
- Identify type of problem: Time Series Forecasting.
# Data Collection & Preprocessing
- Dataset: Monthly Champagne Sales (Perrin Frères).
- Handle missing values (dropna).
- Rename columns and convert Month to datetime format.
- Set Month as the index (Time Series Index).
# Exploratory Data Analysis (EDA)
- Plot sales data to observe trends and seasonality.
- Use descriptive statistics (mean, variance).
- Perform stationarity tests (ADF test).
# Feature Engineering
- Differencing to remove trend/seasonality (1st difference, seasonal difference).
- Create new features:
- Sales First Difference
- Seasonal First Difference
# Feature Selection
- Check stationarity of differenced series using ADF test.
- Use ACF (AutoCorrelation Function) and PACF (Partial AutoCorrelation Function) plots to identify lag dependencies.
# Model Training
- Apply ARIMA / SARIMA models using identified p, d, q, P, D, Q parameters.
- Train the model on historical data.
# Model Testing & Validation
- Split data into train and test sets.
- Evaluate model performance using metrics:
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)
# Output & Visualization
<img width="1257" height="834" alt="Screenshot 2025-08-16 111730" src="https://github.com/user-attachments/assets/7474c347-f175-4779-961a-6cdab9d94768" />
