# Credit Card Default Prediction

This repository contains code and resources for a Credit Card Default Prediction model. Credit card default prediction is a critical task for financial institutions to assess and manage credit risk effectively. This project aims to build a machine learning model that can predict whether a credit card customer is likely to default on their payments.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [Deployment](#deployment)


## Introduction

Credit card default occurs when a credit cardholder fails to make the minimum required payment on their credit card debt. Accurately predicting credit card default is essential for financial institutions to minimize losses and make informed decisions regarding lending and credit management. This project involves creating a machine learning model to predict credit card defaults.

## Dataset

The dataset used for this project is available in the `data` directory. It includes the following features:

**Breakdown of Our Features:**

We possess data for 30,000 customers, and the following describes all the available features.

   
- **ID:** ID of each client
- **LIMIT_BAL:** Amount of given credit in NT dollars (includes individual and family/supplementary credit)
- **SEX:** Gender (1 = male, 2 = female)
- **EDUCATION:** (1 = graduate school, 2 = university, 3 = high school, 0,4,5,6 = others)
- **MARRIAGE:** Marital status (0 = others, 1 = married, 2 = single, 3 = others)
- **AGE:** Age in years
- **Scale for PAY_0 to PAY_6 :** (-2 = No consumption, -1 = paid in full, 0 = use of revolving credit (paid minimum only), 1 = payment delay for one month, 2 = payment delay for two months, ... 8 = payment delay for eight months, 9 = payment delay for nine months and above)
- **PAY_0:** Repayment status in September, 2005 (scale same as above)
- **PAY_2:** Repayment status in August, 2005 (scale same as above)
- **PAY_3:** Repayment status in July, 2005 (scale same as above)
- **PAY_4:** Repayment status in June, 2005 (scale same as above)
- **PAY_5:** Repayment status in May, 2005 (scale same as above)
- **PAY_6:** Repayment status in April, 2005 (scale same as above)
- **BILL_AMT1:**  Amount of bill statement in September, 2005 (NT dollar)
- **BILL_AMT2:** Amount of bill statement in August, 2005 (NT dollar)
- **BILL_AMT3:** Amount of bill statement in July, 2005 (NT dollar)
- **BILL_AMT4:** Amount of bill statement in June, 2005 (NT dollar)
- **BILL_AMT5:** Amount of bill statement in May, 2005 (NT dollar)
- **BILL_AMT6:** Amount of bill statement in April, 2005 (NT dollar)
- **PAY_AMT1:** Amount of previous payment in September, 2005 (NT dollar)
- **PAY_AMT2:** Amount of previous payment in August, 2005 (NT dollar)
- **PAY_AMT3:** Amount of previous payment in July, 2005 (NT dollar)
- **PAY_AMT4:** Amount of previous payment in June, 2005 (NT dollar)
- **PAY_AMT5:** Amount of previous payment in May, 2005 (NT dollar)
- **PAY_AMT6:** Amount of previous payment in April, 2005 (NT dollar)
- **default.payment.next.month:** Default payment (1=yes, 0=no)

## Data Preprocessing

Data preprocessing is crucial for cleaning and preparing the dataset for model training. It includes handling missing values, encoding categorical features, and scaling numerical features. The Jupyter Notebook provides detailed preprocessing steps.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) is performed to gain insights into the dataset. The notebook contains visualizations and summary statistics to better understand the data.

## Feature Engineering

Feature engineering involves creating new features or transforming existing ones to improve model performance. In this project, feature engineering techniques are applied to enhance the predictive power of the model.

## Model Building

Multiple machine learning models are trained and evaluated for credit card default prediction. The notebook includes code for training and testing different models, such as logistic regression, decision trees, and ensemble methods.

## Evaluation

The model's performance is assessed using various evaluation metrics such as accuracy, precision, recall, and F1-score. The notebook provides a comprehensive analysis of the model's effectiveness.

## Future Work
- Deployment
To deploy the credit card default prediction model. This may include using cloud services, APIs, or other deployment methods.
