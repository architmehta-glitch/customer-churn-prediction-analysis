# Customer Churn Prediction: A CS1 Actuarial Statistics Approach

## Executive Summary
Analysis of 7,043 telecom customer records to identify and quantify the factors driving customer churn. This project applies actuarial statistical methods — probability modelling, hypothesis testing, regression, GLMs, Bayesian credibility theory, and simulation — to assess and predict customer lapse risk.

## Business Objective
Build a statistical framework to estimate the probability that a customer churns, and identify which contractual, service, and billing characteristics are the strongest risk indicators. This mirrors the persistency and lapse-rate questions an actuary addresses when pricing and reserving for a book of policies.

## Dataset Overview
- **Records:** 7,043 customers
- **Target Variable:** `Churn` — customer churned (Yes) or remained (No) during the observation period
- **Key Features:** contract type, tenure, internet service type, payment method, paperless billing, senior citizen status, monthly and total charges

## Key Findings
- Overall churn rate: 26.6%
- Strongest predictors from the GLM: Contract type (Two year vs Month-to-month, p < 2e-16) and Internet Service type (Fiber optic, p < 2e-16)
- Monthly Charges alone was not a significant independent predictor once Contract and Internet Service were controlled for

## Technical Skills Applied
- **Language:** R
- **Statistical Methods:** Probability distributions, MLE and method of moments, hypothesis testing (t-test, F-test, chi-squared), correlation, multiple linear regression, generalized linear models (logistic regression), Bayesian credibility theory (EBCT), Monte Carlo simulation
- **Tools:** Base R, data cleaning, model fitting, data visualization

## Actuarial Relevance
This project demonstrates CS1-level actuarial competencies:
- Probability and distribution theory applied to lapse/churn events
- Statistical inference and significance testing for risk factor identification
- Regression and GLM-based risk modelling
- Bayesian/credibility methods for segment-level rate estimation, as used in experience rating
- Simulation-based estimation of financial impact and intervention scenarios

## Files
- `customer-churn-prediction-actuarial-analysis.ipynb` - Main analysis notebook
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` - Dataset

## Kaggle Project
https://www.kaggle.com/code/architmehta1908/customer-churn-prediction-actuarial-analysis

## Author
Archit Mehta - Actuarial Aspirant (CM1, CS1)
