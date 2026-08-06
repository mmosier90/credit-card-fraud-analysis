## Executive Summary

The poster below summarizes the complete workflow, including data preparation, exploratory analysis, statistical visualizations, feature importance analysis, and the project's primary findings.

![Project Poster](screenshots/ccfraud-poster.JPG)

---

## Business Question

Can customer demographics and transaction characteristics help explain fraudulent credit card transactions?

Using approximately 10,000 anonymized credit card transactions, this project explores patterns in customer behavior, geography, and purchasing activity to identify variables most strongly associated with fraud.

Because fraudulent transactions represent only **0.55%** of all observations, the dataset also illustrates the challenges of analyzing highly imbalanced data.

---

## Technical Skills Demonstrated

- R
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Statistical Visualization
- Correlation Analysis
- Feature Importance Analysis
- Geographic Visualization
- Data Transformation

---

## Data Preparation

The dataset was cleaned and prepared in R before analysis.

Preparation included:

- Removing unused variables
- Cleaning merchant names
- Converting Date of Birth into Age
- Creating dummy variables for gender
- Log-transforming skewed variables
- Preparing numeric variables for statistical analysis

---

## Exploratory Analysis & Key Findings

The analysis explored relationships between customer demographics, transaction characteristics, and fraudulent activity through statistical visualizations, correlation analysis, feature importance, and geographic mapping.

Key findings included:

- Fraud represented only **0.55%** of all transactions, highlighting the challenges of working with highly imbalanced data.
- Transaction amount showed the strongest relationship with fraudulent activity.
- Customer age, gender, and city population demonstrated little predictive value.
- Geographic differences existed but were not statistically meaningful predictors of fraud.
- Overall, fraudulent transactions appeared to be driven more by purchasing behavior than by customer demographics.

---

## Future Improvements

- Train and evaluate a complete Random Forest classifier
- Compare multiple machine learning models
- Address class imbalance through resampling techniques
- Evaluate precision, recall, ROC-AUC, and F1-score
- Build an interactive dashboard for fraud monitoring
- Deploy the workflow as a reproducible analytical pipeline

---

## Data Source

Kaggle Credit Card Fraud Detection Dataset
https://www.kaggle.com/datasets/mishra5001/credit-card/data 
