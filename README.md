# FDV
## Week 2 tasks 

## Task 1 : Cardio Vascular disease(CVD) prediction 

# Cardiovascular Disease Risk Prediction

## Introduction
This project aims to develop a predictive model for identifying the risk of cardiovascular disease (CVD) using machine learning techniques. The provided dataset includes various medical indicators such as age, gender, cholesterol levels, and blood pressure, along with a binary target variable indicating the presence or absence of CVD.

## Problem Statement
The task involves conducting Exploratory Data Analysis (EDA) followed by model development to accurately predict the presence or absence of CVD based on the given features.

## Dataset
The dataset contains the following columns:
- Age: Age of the individual (in years)
- Gender: Gender of the individual (1 = Male, 0 = Female)
- Cholesterol: Cholesterol level (in mg/dL)
- Blood Pressure: Systolic blood pressure (in mmHg)
- ... (Other relevant features)
- CVD: Target variable indicating the presence (1) or absence (0) of cardiovascular disease

## Methodology
1. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of features
   - Explore correlations between variables
   - Identify potential patterns or outliers

2. **Model Development**:
   - Logistic Regression: Build a logistic regression model
   - Decision Tree: Construct a decision tree model

## Results
The models were evaluated using the F1-score metric, which considers both precision and recall. The results are as follows:

| Model                 | F1-Score    |
| :---:                 | :---:       | 
| Logistic Regression   | 0.70        | 
| Decision Tree         | 0.99        | 

The decision tree model outperformed logistic regression, achieving a significantly higher F1-score and demonstrating lower type-II errors.

## Conclusion
Based on the results, the decision tree model is recommended for identifying individuals at risk of cardiovascular disease in this dataset. Further optimizations and model enhancements could be explored to improve predictive performance.

## Task 2 : Injury severity prediction from aviation dataset

## Introduction

This project focuses on predicting the severity of injuries in airline accidents using machine learning techniques. The dataset provided contains various attributes related to aviation incidents, such as purpose of flight, air carrier, and injury counts, along with the target variable indicating the severity of injuries.

## Problem Statement

Predicting injury severity in airline accidents is a multiclass classification problem, where the severity levels include fatal and non-fatal injuries.

## Dataset

The dataset comprises the following columns:
- Purpose of flight
- Air carrier
- Total fatal injuries
- Total serious injuries
- Total minor injuries
... and other relevant attributes.
- Injury severity: The target variable with classes indicating severity levels (e.g., fatal, non-fatal).

## Methodology

1. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of features.
   - Handle missing values:
     - Experiment with imputation techniques such as mean, median, and KNN imputation.
   - Explore correlations between variables.

2. **Model Development**:
   - Random Forest Classifier
   - Decision Tree

## Results

The models were evaluated using the F1-score metric, which considers both precision and recall. The results are visualized below:

### Random Forest Classifier

![Random Forest Results](/media/image.png)

### Decision Tree

![Decision Tree Results](/media/image2.png)

The decision tree model outperformed the random forest model based on the F1-score metric.

## Conclusion

Based on the experimentation with different imputation techniques during the EDA phase, it was observed that imputation with the mode yielded the best results for this dataset. Therefore, imputing missing values with the mode is recommended for this injury severity prediction task. Further optimizations and model enhancements could be explored to improve predictive performance.





