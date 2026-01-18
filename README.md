Customer Term Deposit Prediction
Project Overview

This project aims to predict whether a customer will subscribe to a term deposit based on demographic, financial, and marketing campaign data. The objective was to build a machine learning classification model that helps banks identify potential customers who are more likely to respond positively to term deposit offers.

The dataset contains information related to customer attributes, previous marketing interactions, and economic indicators. Using this data, a predictive model was developed to support data-driven decision making in banking marketing strategies.

Dataset Description
Feature Variables

age – Age of the customer

job – Type of job

marital – Marital status

education – Level of education

default – Credit in default or not

balance – Average yearly balance

housing – Housing loan status

loan – Personal loan status

contact – Communication type

day – Last contact day of the month

month – Last contact month

duration – Duration of last contact

campaign – Number of contacts performed

pdays – Days since previous contact

previous – Number of contacts before this campaign

poutcome – Outcome of previous marketing campaign

Target Variable

deposit – Whether the customer subscribed to a term deposit (Yes/No)

Objective

To analyze customer behavior from marketing data

To preprocess categorical and numerical features

To build a classification model for deposit prediction

To evaluate model performance using appropriate metrics

Technologies Used

Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-Learn

Jupyter Notebook

Project Workflow

Data Collection and Understanding

Loaded and explored the dataset

Checked for missing values and class imbalance

Exploratory Data Analysis

Analyzed distribution of numerical features

Examined impact of job, education, and loan status on deposit

Visualized correlations

Data Preprocessing

Encoding categorical variables

Feature scaling

Train-test split

Model Building

Implemented classification algorithms

Hyperparameter tuning

Model Evaluation

Accuracy

Precision, Recall, F1-Score

Confusion Matrix

Key Insights

Customers with higher balance showed more interest in term deposits

Duration of last call had strong influence on prediction

Previous campaign outcome played a major role

Housing and personal loan holders were less likely to subscribe

Results

The classification model successfully predicted customer subscription behavior and can be used to optimize marketing campaigns by targeting the right audience.

Repository Structure
├── dataset/
├── notebooks/
├── models/
├── README.md

Future Improvements

Implement advanced models such as Random Forest, XGBoost

Handle class imbalance using SMOTE

Deploy the model using Flask or Streamlit

Feature selection for better generalization

Author

Muhammad Waseem
Machine Learning & Data Science Enthusiast
