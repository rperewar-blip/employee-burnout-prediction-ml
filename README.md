Employee Burnout Prediction, Risk Classification & Forecasting using Machine Learning
Overview

Employee burnout is a growing organizational challenge that impacts productivity, retention, and employee well-being. This project develops a machine learning framework to predict burnout rates, classify employees into risk categories, and forecast future burnout trends.

The objective is to enable organizations to move from reactive intervention to proactive workforce management using data-driven insights.

Problem Statement

Organizations often detect burnout only after it negatively affects performance. This project aims to:

Predict employee burnout rate

Classify employees into low, medium, and high-risk groups

Forecast future burnout trends

Identify key drivers contributing to burnout

Dataset

18,590 employee records

20 engineered features

Target variable: Burnout Rate (0–1 scale)

Key variables include:

Mental fatigue score

Resource allocation

Designation

Work environment factors

Project Workflow
1. Data Cleaning & Preprocessing

Handling missing values

Feature encoding

Normalization

Feature engineering

2. Exploratory Data Analysis (EDA)

Correlation matrix

Distribution analysis

Burnout trend visualization

3. Regression Modeling

Models tested:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

Best Model: Gradient Boosting
R² Score: 0.927
RMSE: 0.0529
MAE: 0.0433

4. Classification Modeling

Model Used:

Random Forest Classifier

Accuracy: 87.6%
F1 Score: 0.88

Risk Distribution:

Low Risk: 4,899 employees

Medium Risk: 10,807 employees

High Risk: 2,884 employees

5. Feature Importance Analysis

Top Predictors:

Mental fatigue score

Resource allocation

Workload interaction features

6. Time-Series Forecasting

Prophet used to forecast next 6 months

Results indicate gradual upward trend in burnout levels

Key Insights

Mental fatigue is the strongest predictor of burnout.

Workload allocation significantly impacts employee risk levels.

Nearly 15% of employees fall into high-risk category.

Forecasting suggests potential future increase without intervention.

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Gradient Boosting

Random Forest

Prophet

Matplotlib

Seaborn

Jupyter Notebook

Business Impact

This framework enables organizations to:

Detect burnout early

Prioritize high-risk employees

Optimize workload distribution

Improve retention strategies

Enhance employee well-being

Future Improvements

Deploy as web application (Streamlit/Flask)

Integrate real-time HR dashboard

Expand dataset with psychological survey inputs

Apply deep learning techniques

Author

Rishabh Perewar
Master’s in Business Analytics
Saint Peter’s University
