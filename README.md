## Parameter_Importance_Health || Sleep Health and Lifestyle Analysis

This project focuses on analyzing and modeling the relationship between lifestyle factors and sleep quality using a dataset on sleep health and lifestyle. The goal is to explore how different variables influence sleep quality and to build predictive models for identifying potential sleep disorders.

# Project Overview
The dataset used in this project is Sleep_health_and_lifestyle_dataset.csv, which contains information on individuals' sleep patterns, lifestyle habits, and health metrics.

# Key Features of the Project
Data Preprocessing: The dataset is cleaned and transformed, with unnecessary columns removed and categorical variables encoded.

# Feature Engineering:
-> Blood pressure data is split into Blood High and Blood Low components.
-> BMI categories are numerically encoded.
-> Gender is represented using binary variables.
-> Sleep disorders are categorized and encoded for further analysis.
# Linear Regression Modeling:
-> An iterative feature selection process is employed to build a linear regression model predicting sleep quality. The model is trained and evaluated using the R-squared (R^2) metric.
-> A plot is generated to show how the number of features affects the model's performance.
# Sleep Disorder Prediction:
-> A second linear regression model is created to predict whether an individual may have a sleep disorder based on lifestyle and health factors.
-> The model's performance is evaluated using Mean Squared Error (MSE) and R^2, and the results are presented.
# Results
The project demonstrates the importance of feature selection in regression modeling and provides insights into the factors that most significantly influence sleep quality and sleep disorders.

# Requirements:
Python 3.x
Libraries:
-> numpy
-> pandas
-> scikit-learn
-> matplotlib
# Usage
To run the project, simply load the dataset and execute the script. The code will preprocess the data, build regression models, and output the results, including performance metrics and plots.

# Disclaimer
This project is provided for educational purposes only. The dataset and models are used for demonstration and learning and should not be used for any clinical or commercial applications.
