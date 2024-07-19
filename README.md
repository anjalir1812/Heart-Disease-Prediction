# Prediction of Heart Diseases Using Machine Learning Models

## Introduction

This project focuses on predicting heart diseases using various machine learning models. Given a dataset of clinical and demographic variables, we aim to create an efficient and accurate predictive model that can help in early diagnosis and treatment of heart diseases.

## Models and Methodology
We employed several machine learning algorithms to predict heart disease

1. Logistic Regression

2. Decision Tree

3. Random Forest

4. K-Nearest Neighbors (KNN)
   
Data preprocessing involved feature scaling and engineering. The dataset was split into training and testing sets, and each model was evaluated for performance.

## Data Overview

The dataset used for this project includes clinical and demographic information from patients globally. The features include:

1. Age
2. Sex
3. Chest Pain Type
4. Blood Pressure (BP)
5. Cholesterol Levels
6. Fasting Blood Sugar
7. EKG Results
8. Max Heart Rate
9. ST Depression
10. Slope of ST Depression
11. No. of majoe vessels
12. Thallium Test Results
13. Diagnosis of Heart Disease
14. Exercise Induced Angnia

## Evaluation Metrics

To evaluate the performance of the models, we used the following metrics:

1. Accuracy: The proportion of true results (both true positives and true negatives) among the total number of cases examined.
2. Precision: The ratio of correctly predicted positive observations to the total predicted positives.
3. Recall: The ratio of correctly predicted positive observations to all observations in the actual class.
4. F1 Score: The weighted average of Precision and Recall.

## Results
The results for each model were as follows:

- Model	Accuracy	F1 Score

- Logistic Regression	74.07%	69.56
- Decision Tree	76.54%	78.65
- Random Forest	83.95%	83.95
- K-Nearest Neighbors	53.08%	53.65

![Screenshot (9)](https://github.com/user-attachments/assets/69fa1555-0375-42d6-befb-1a367cb4b5f2)


## Conclusion

The Random Forest model outperformed the other models in terms of accuracy and F1 score, making it the most suitable model for predicting heart diseases with the given dataset.

