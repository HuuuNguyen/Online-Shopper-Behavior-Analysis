# **README for Online Shopper Behavior Analysis**
## **Project Title**
Online Shopper Behavior Analysis

## **Description**
This project explores the behaviors of online shoppers, using machine learning models to understand how different factors influence purchasing decisions, in order to build predictive models for the purchasing intentions. The analysis helps businesses to tailor their marketing strategies and product offerings more effectively to enhance user engagement and sales.

## **Objectives**
This project aims to analyze the online shoppers'behavior to identify key patterns and factors influencing purchasing decisions. By analyzing this dataset, we will be able to:
1. Analyze the correlation between the browsing behaviors and purchasing decisions
2. Identify which features influence the purchasing intention of online shoppers and Predict whether a shopper will generate revenue
3. Compare which models is more efficient compared to the other (Logistic Regression/KNN Classifier)
 
## **Contents of the Notebook**
### Introduction: 
Overview of the dataset and the project's objectives.

### Data Cleaning:
- Removing misssing values
- Encoding the categorical variables

### Data Exploration: 
- Univariate for each features in order to undertand their distributions
- Bivariate analysis between different features with the 'sold' features in order to investigate which factors affect the purchasing decisions.

### Model Building:
- Logistic Regression: Using RFE method to find the 5 optimal features to be included in the model
- KNN Classifier: Used the 5 optimal features from the former model to be included in the model
- Conclusion: The KNN Classifier appears to be more effective compared to Logistic Regression due to higher accuracy score for both training and testing set. However, the difference is not much to conclude that the KNN Classifier is more superior in comparison.
