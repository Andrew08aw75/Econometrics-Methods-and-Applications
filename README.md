# Econometrics – Methods and Applications

## Overview

This repository contains a practical econometrics exercise developed as part of the **Econometrics: Methods and Applications** course offered by Erasmus University Rotterdam.

The project focuses on applying statistical analysis and econometric techniques to investigate the relationship between customer age and average daily holiday expenditures.

Using a dataset from a travel agency, the exercise explores customer spending patterns, applies simple linear regression models, and develops predictive insights to support customer segmentation and recommendation strategies.

## Project: Training Exercise 1.1 – Customer Age and Holiday Expenditures

### Business Context

A travel agency aims to improve its recommendation strategies by understanding the relationship between customer age and average daily expenditures during holidays.

The dataset contains 26 observations with two variables:

- **Age:** Customer age.
- **Expenditures:** Average daily holiday expenditures.

The main objective is to explore customer spending behavior and investigate whether age can help explain and predict holiday expenditure patterns.

### Methodology

The project follows a structured statistical and econometric workflow.

#### 1. Data Exploration and Descriptive Statistics

- Dataset inspection and preparation.
- Descriptive statistical analysis.
- Calculation of mean, standard deviation, minimum, and maximum values.
- Distribution analysis using histograms.

#### 2. Data Visualization

- Histograms to examine age and expenditure distributions.
- Scatter plots to investigate relationships between variables.
- Regression plots to visualize the estimated linear relationship.

#### 3. Econometric Modeling

Simple Linear Regression was applied to examine the relationship between customer age and daily holiday expenditures.

The Ordinary Least Squares (OLS) method was implemented using:

- Statsmodels.
- Scikit-learn.

The regression model was used to estimate coefficients, analyze statistical significance, and evaluate explanatory power.

#### 4. Customer Segmentation

The analysis explored differences in average expenditures between two customer groups:

- Customers aged 40 or above.
- Customers below 40 years old.

This segmentation provided additional insights into spending behavior and potential differences between customer groups.

#### 5. Predictive Analysis

The estimated regression model was used to predict average daily expenditures for hypothetical customers aged 50 and 25.

These predictions illustrate how regression models can support customer profiling and recommendation strategies.

## Key Findings

The analysis identified the following results:

- The dataset contains 26 customer observations.
- Average daily expenditure across all customers was approximately 101.12.
- Customers aged 40 or above had an average expenditure of approximately 95.85.
- Customers below 40 had an average expenditure of approximately 106.38.
- The estimated regression coefficient for age was negative (-0.3336).
- The model achieved an R-squared value of approximately 0.338.

The analysis also highlighted differences in spending patterns across age groups, suggesting that customer segmentation may provide additional insights beyond analyzing the entire dataset as a single population.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- Jupyter Notebook
- Econometrics
- Statistical Analysis
- Ordinary Least Squares (OLS)
- Linear Regression
- Predictive Modeling

## Key Skills Demonstrated

- Exploratory Data Analysis (EDA).
- Descriptive Statistics.
- Statistical Data Visualization.
- Econometric Modeling.
- Ordinary Least Squares Regression.
- Linear Regression Implementation.
- Statistical Model Interpretation.
- Customer Segmentation.
- Predictive Analytics.
- Business-Oriented Data Analysis.

## Repository Contents

- `Training_Exercise_1.1.ipynb`: Jupyter Notebook containing the complete analysis, data exploration, visualizations, regression modeling, and expenditure predictions.

## Learning Outcomes

This exercise demonstrates the application of econometric methods and statistical analysis to a practical business problem.

It highlights how regression techniques, descriptive statistics, and customer segmentation can be used to identify behavioral patterns and generate insights to support business recommendations.

---

**Course:** Econometrics: Methods and Applications  
**Institution:** Erasmus University Rotterdam  
**Platform:** Coursera  
**Exercise:** Training Exercise 1.1 – Customer Age and Holiday Expenditures
