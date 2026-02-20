# customer-lifetime-value-prediction
This project builds a predictive model to estimate customer lifetime value using early behavioral and engagement signals. The goal is to forecast future revenue, support user segmentation, and guide business decisions around acquisition, retention, and investment prioritization using data-driven insights.

📊 Customer Lifetime Value (LTV) Prediction
Project Overview
This project builds a predictive model to estimate customer lifetime value (LTV) using early behavioral and engagement signals. The objective is to forecast future revenue per user and support data-driven decisions in growth, retention, and marketing investment.
Business Problem
Not all users generate the same long-term value. Accurately predicting LTV allows businesses to:
Allocate acquisition spend more efficiently
Prioritize high-value users for retention
Evaluate growth strategies before long-term revenue is realized
Dataset
The dataset contains user-level behavioral features, including:
Activation status
Orders and revenue in the first 90 days
User tenure and recency of activity
Acquisition channel information
Target variable:
LTV proxy based on observed revenue behavior
Methodology
Data cleaning and validation
Feature engineering and selection
Train-test split
Regression modeling using Random Forest
Model evaluation using MAE and R²
Interpretation of results from a business perspective
Key Results
The model captures meaningful revenue patterns from early user behavior
Demonstrates how predictive modeling can inform budget allocation and customer strategy
Provides a practical framework adaptable to real production datasets
Skills Demonstrated
Predictive modeling
Feature engineering
Model evaluation
Business-driven data science
End-to-end ML workflow
Tools & Libraries
Python
pandas, numpy
scikit-learn
matplotlib / seaborn