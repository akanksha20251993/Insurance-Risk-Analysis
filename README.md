# Insurance-Risk-Analysis
Insurance claim risk analysis using R with logistic regression, linear regression, PCA, and t-SNE.
##  Project Overview
This project analyzes insurance claim risk using a real-world insurance dataset. The objective is to identify key factors that influence whether a customer files an insurance claim and to understand patterns associated with higher risk. The analysis focuses on claim frequency modeling and risk interpretation using statistical and machine learning techniques in R.

## Dataset Description
The dataset contains insurance customer information including:
- Customer demographics (age, income, marital status)
- Driving and exposure characteristics (motor vehicle record points, commute time, number of young drivers)
- Vehicle and location indicators
- Claim outcomes (claim occurrence and claim amount)

## Tools & Technologies
- R
- dplyr
- ggplot2
- Logistic Regression
- Linear Regression
- PCA (Principal Component Analysis)
- t-SNE (t-distributed Stochastic Neighbor Embedding)

## Analysis Performed
- Data preprocessing and feature selection using imputed variables
- Exploratory data analysis to understand claim distributions
- Logistic regression to model insurance claim probability (frequency modeling)
- Linear regression to analyze claim severity for customers with claims
- Dimensionality reduction (PCA and t-SNE) to visualize underlying risk patterns

## Key Insights
- Claim risk increases significantly for customers living in urban areas, those with higher motor vehicle record points, and households with young drivers.
- Older, higher-income, and married customers show lower probability of filing claims.
- Longer customer tenure is associated with reduced claim risk.
- Behavioral and exposure-related factors are stronger predictors of claims than demographic attributes such as gender or car characteristics.

##Conclusion
This project demonstrates applied data analytics skills in insurance risk modeling, including data cleaning, statistical modeling, and result interpretation. The findings highlight how insurers can use data-driven insights to assess customer risk more effectively and support underwriting and pricing decisions.
