📊 Credit Card Default Prediction — EDA & ML-Ready Dataset

This project focuses on analyzing and preparing a real-world Credit Card Default dataset for machine learning.
The goal is to understand customer behaviour, identify default patterns, engineer meaningful features, and build a fully cleaned dataset ready for predictive modeling.

The final machine learning model (next phase) will use inputs like age, gender, marital status, credit limit, last bill amount, and last payment amount to predict the probability of a customer defaulting.

✅ Project Description

The project includes:

🔹 Data Cleaning

Renaming ambiguous columns

Fixing invalid categorical values

Handling outliers in BILL_AMT, PAY_AMT, and delay variables

Removing duplicates and formatting data for consistency

🔹 Exploratory Data Analysis (EDA)

Univariate, bivariate, and multivariate visualizations

Analysis of demographics, spending behaviour, payment patterns

Understanding target imbalance (80–20 default vs non-default)

🔹 Feature Engineering

Creating new behavioural features:

avg_bill

avg_payment

avg_delay

Binning continuous values into categories

One-hot encoding categorical variables

Scaling numerical features

Removing irrelevant columns

🔹 Machine Learning Preparation

Producing a final cleaned, engineered, scaled dataset

Ready for classification models like Logistic Regression, Random Forest, and XGBoost

📁 File Descriptions
✅ 1. credit_default_scaled.csv

This file contains the fully cleaned, encoded, engineered, and scaled dataset.

Includes only relevant features for modeling

All categorical variables are machine-readable

Numerical features are scaled

Ready to be used directly in ML algorithms

✅ 2. eda.ipynb

The Jupyter Notebook used to:

Clean raw data

Explore distributions and relationships

Visualize default patterns

Perform feature engineering

Build the final dataset

This is the full analytical workflow for the project.

✅ 3. Credit_Card_Default_Report.pdf

A polished, professionally written PDF summarizing:

Dataset overview

Data cleaning process

EDA findings

Feature engineering

Recommendations for model building

Perfect for portfolio and presentation use.

📈 Next Steps

Future versions of this project will include:

Model training and evaluation

Hyperparameter tuning

Feature importance analysis

Deployment using FastAPI or Streamlit

🛠 Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn
