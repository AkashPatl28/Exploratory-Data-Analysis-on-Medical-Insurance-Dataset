# Medical Insurance Cost Analysis and Prediction
## Project Overview

This project focuses on exploratory data analysis (EDA) and regression modeling using a medical insurance dataset.
The goal is to understand the factors affecting insurance charges and evaluate a regression model using the R² score.

The project starts with data exploration and ends with building a machine learning model to predict insurance costs.

## Dataset Description

The dataset contains personal and medical attributes of individuals along with their insurance charges.

Features used:

 1.  age – Age of the individual

 2.  sex – Gender

 3.  bmi – Body Mass Index

 4.  children – Number of children/dependents

 5.  smoker – Smoking status

 6.  region – Residential region

 7.  charges – Medical insurance cost (target variable)

## Exploratory Data Analysis (EDA)

* EDA was performed to:

  * Understand data distribution

  * Identify relationships between features and insurance charges

  * Analyze the impact of smoking, age, and BMI on medical costs

  * Detect patterns and trends using visualizations

This step helped in selecting suitable features for regression modeling.

## Machine Learning Model

 After EDA, a Linear Regression model was implemented.

 * Steps followed:

 1. Encoding categorical variables using Label Encoding

 2. Splitting data into training and testing sets

 3. Training a Linear Regression model

 4. Predicting insurance charges

 5. Evaluating model performance using R² score

## Model Evaluation

 * Metric used: R² Score

   * R² explains how well the model predicts medical insurance charges based on input features.

   * A higher R² value indicates better predictive performance.

## Model Performance
 * Algorithm: Linear Regression
 * Train-Test Split: 80/20
 * R² Score: 0.78

## Technologies Used

 * Python

 * Pandas

 * NumPy

 * Matplotlib

 * Seaborn

 * Scikit-learn

 * Jupyter Notebook

## How to Run the Project

 1. Clone the repository

 2. Open the Jupyter Notebook

 3. Run all cells sequentially

 4. View EDA insights and R² score output

## Key Takeaways

 * Smoking status has a major impact on insurance charges

 * Age and BMI significantly influence medical costs

 * Linear Regression provides a reasonable baseline model

 * R² score validates the effectiveness of the regression approach

## Future Improvements

 * Try advanced models like Random Forest or Gradient Boosting

 * Feature scaling and hyperparameter tuning

 * Add cross validation

 * Improve model accuracy further
