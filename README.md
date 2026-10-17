# Predicting Credit Card Defaults

This project is a part of the ADS-505 course in the Applied Data Science Program at the University of San Diego. 

## Project Objective 
The business aim is to reduce the loss of revenue occurred due to clients defaulting on their monthly payments. Early outreach programs can be developed by the Credit Risk team and applied to customers most likely to default. In order to identify those customers, a classification model will be developed that also ranks them by their propensity to default on the next months payment. A successful model will predict defaulters better than the baseline model while a successful outreach campaign would reduce the percent of overall credit card default for the quarter by 1%

## Contributors
- Mia Arnold
- Harshali Gaikwad
- Katia Paredes

## Contributions
- Mia Arnold: Problem Statement, Business Objective, Data Description, Linear Discriminant Analysis Model, and Adaboost Model
- Harshali Gaikwad: Data Preprocessing, Modeling Pipeline, Random Forest Model, Logistic Regression Model, Discussion and Conclusion
- Katia Paredes: Exploratory Data Analysis, Feature Engineering, Neural Network, Descison Tree, Lift Charts

## Methods Used
- Predictive Modeling

## Technologies
- Python Version 3.14.7
- Juypter Notebook

## Required Packages
- Pandas
- MatPlotLib
- NumPy
- Sklearn
- iPython

## Project Description
This project aims to develop a predictive model that accurately identifies higher-risk customers likely to default on their credit card payments and estimates each customer’s probability of defaulting in the following month. Banks can use this information to target clients for early outreach programs to reduce overall credit card default rates. 

## Data & Data Description
The dataset is a xls file that includes 23 attributes and 30,000 instances. It was found on the UCI Repository. There is a mix of binary, categorical and numerical variables. There are no missing values but the outcome variable is imbalanced.

Yeh, I. (2016). *Default of Credit Card Clients* UCI Machine Learning Repository. (https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)

*The dataset used for modeling was cleaned and included engineered features. There were a total of 41 final attributes. The cleaned data used for modeling can be found in the `data` folder under the name `credit_default_engineered.csv`.

# Instructions
Download the cleaned dataset with engineered features, `credit_default_engineered.csv`, then open the file titled `final_project.ipynb`. This file contains all EDA, Modeling, and Discussion.

# License 
This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.
This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Acknowledgments
To all our friends, family, pets and peers who helped us along the way.
