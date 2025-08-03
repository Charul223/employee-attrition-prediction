# employee-attrition-prediction
A Machine Learning project for predicting employee attrition. Includes data preprocessing, model training, and evaluation.

This project aims to predict whether an employee is likely to leave using various classification algorithms like Logistic Regression and Random Forest.

## Problem statement:
Employee attrition greatly impacts financial health, productivity and morale of a company. This also leads to incresed training and hiring costs, decreasing productivity. Understanding this problem and finding and implementing solutions for the same is crucial for maintaining a stable and motivated workforce.
Even in today's unpredictable job market, employee attrition is crucial- even post layoffs. This is meaningful as it helps in retaining key talent and reduce turnover costs.

## Dataset:
Size: 902 rows, 16 features

## Technologies & Libraries

- Python
- Google Colab
- Pandas, NumPy
- Matplotlib
- Scikit-learn

## Features used:
Key features include:
-Age
-Emp. Group
-Function
-Location
-Tenure
-Gender
-Marital Status

## Model Workflow:

The following steps were followed to build the attrition prediction model:

1. **Data Loading and Exploration**
-Loaded the dataset using pandas
-Explored data structure, types, and missing values. Performed partial EDA.
-Visualized basic distributions and feature relationships

2. **Data Preprocessing**
-Filled or handled missing values
-Merged rare categories under a common label (e.g., "Other group")
-Encoded categorical variables using LabelEncoder
-Separated features (X) and target (y)

3. **Train-Test Split**
-Split data into 80% training and 20% testing using train_test_split

4. **Model Building & Training**
Trained multiple models for comparison:
-Logistic Regression
-Decision Tree Classifier
-K-Nearest Neighbors (KNN)
-Random Forest Classifier
-Fit each model on the training dataset

5. **Model Evaluation**
Evaluated each model on the test set using:
-Accuracy
-Classification Report
-Confusion Matrix

Selected the best-performing model for final prediction

6. **Prediction**
Used the selected model to predict attrition on unseen data




