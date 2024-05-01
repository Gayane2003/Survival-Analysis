# Telco Customer Churn Analysis
Welcome to the Telco Customer Churn Analysis project!

This project aims to analyze customer churn in a telecommunications (Telco) dataset using survival analysis techniques. Customer churn, or attrition, is a critical issue for businesses, and understanding the factors influencing churn can help companies develop effective retention strategies.

# Project Overview
In this project, we employ survival analysis to model customer tenure (survival time) and predict the probability of churn over time. We utilize an accelerated failure time (AFT) model with the Loggaussian distribution to fit the survival data. The analysis includes:

Exploratory data analysis (EDA) of the Telco dataset.
Fitting AFT models with different distributions to identify the best-fitting model.
Evaluation of model performance using information criteria (AIC, BIC).
Interpretation of model coefficients and significance testing.
Estimation of customer lifetime value (CLV) and its association with key predictors.
Visualization of CLV trends and insights.
# Code Overview
The provided R code conducts the following tasks:

Data Preprocessing: Reads the Telco dataset and preprocesses it for analysis, including encoding categorical variables and transforming the churn variable.
Model Fitting: Fits AFT models with different distributions to the survival data and evaluates model performance using AIC and BIC.
CLV Analysis: Estimates CLV based on the fitted AFT model and visualizes CLV trends by customer segments.

# Getting Started
To replicate the analysis and explore the code, follow the instructions below:

Clone or download the repository to your local machine.
Install R and the required packages (e.g., survival, ggplot2).
Run the R script to execute the survival analysis code and generate results.

# License
This project is licensed under the MIT License.

