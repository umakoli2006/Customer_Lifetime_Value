# Customer_Lifetime_Value
Customer Lifetime Value Prediction Model

Project Overview

This project predicts the Customer Lifetime Value (LTV) of customers based on their purchase behavior. The project uses customer transaction data to calculate important customer-level features such as Recency, Frequency, and Average Order Value (AOV) and then applies a Random Forest Regression model to predict LTV.

The predicted LTV is also used to divide customers into Low, Medium, and High LTV segments.

Objectives

Analyze customer purchase transactions.

Calculate customer-level Recency, Frequency, and AOV.

Build a machine learning model for LTV prediction.

Evaluate the model using MAE and RMSE.

Predict LTV for all customers.

Segment customers based on predicted LTV.

Save the final predictions and analysis results as CSV files.

Tools and Technologies

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Joblib

Dataset

A customer transaction dataset was created for this project with transaction-level information.

Main columns:

Customer_ID

Order_Date

Category

Quantity

Unit_Price

Total_Amount
