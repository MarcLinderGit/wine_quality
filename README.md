# Predicting Wine Quality with Regularization

## Introduction

In this data analysis project, I aim to explore feature selection techniques and the impact of regularization on a logistic regression model's performance. The dataset under examination is derived from a survey on eating habits and physical condition, with the objective of predicting whether a survey respondent is obese or not. I will employ various methods to select an optimal set of features for the model and evaluate its performance.

Data source: [UCI Machine Learning Repository - Wine Quality](https://archive.ics.uci.edu/dataset/186/wine+quality)

## Methods and Objectives

My project will follow these main steps:

1. **Data Loading and Inspection**: I start by loading the dataset and performing an initial inspection to gain insights into its structure, including the available features and the target variable.

2. **Logistic Regression Model**: As a baseline, I create a logistic regression model without any regularization to establish a starting point for model performance.

3. **Feature Selection with Regularization**: I explore feature selection techniques using both L1 (Lasso) and L2 (Ridge) regularization methods. L1 regularization helps in selecting a subset of the most important features by setting some coefficients to zero, while L2 regularization controls overfitting by penalizing large coefficients.

4. **Hyperparameter Tuning**: I perform hyperparameter tuning for the regularization strength parameter, C, using GridSearchCV. This allows me to find the optimal C value that maximizes model performance.

5. **Visualizing Results**: To provide a comprehensive overview, I visualize the results of the hyperparameter tuning process by plotting the F1 score as a function of different C values. This helps me identify the optimal C value for my logistic regression model.

Throughout the project, I will examine how regularization impacts the model's performance and the selection of an optimal set of features for prediction. By comparing different regularization methods and hyperparameter tuning, I aim to identify the most effective approach for improving model accuracy and interpretability.

Let's delve into the code and explore these methods in detail.