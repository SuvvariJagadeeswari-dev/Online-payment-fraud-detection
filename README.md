# Online-payment-fraud-detection
# Introduction
Online payment is the most popular transaction method in the world today. However, with an increase in online payments also comes a rise in payment fraud. The objective of this notebook is to train machine learning models for identifying fraudulent and non-fraudulent payments. The dataset is collected from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments.

The dataset consists of 10 variables:

* step: represents a unit of time where 1 step equals 1 hour
* type: type of online transaction
* amount: the amount of the transaction
* nameOrig: customer starting the transaction
* oldbalanceOrg: balance before the transaction
* newbalanceOrig: balance after the transaction
* nameDest: recipient of the transaction
* oldbalanceDest: initial balance of recipient before the transaction
* newbalanceDest: the new balance of recipient after the transaction
* isFraud: fraud transaction

# Project Overview
The Online Payments Fraud Detection application is designed to predict fraudulent transactions in online payment systems using advanced machine learning techniques. With the growing risk of online payment fraud, this model helps financial institutions and e-commerce platforms identify suspicious transactions in real-time.

This project focuses on:

Real-time fraud detection by integrating machine learning models into the payment processing system.
Interactive interface for users to input transaction details and receive immediate feedback on transaction validity.
Comprehensive feature engineering and data reduction techniques to optimize model performance.

# Python Libraries
pandas, numpy, seaborn, matplotlib, tabulate, sklearn

# Conclusion
The best performing model is Random Forest for identifying fraudulent and non-fraudulent payments.
