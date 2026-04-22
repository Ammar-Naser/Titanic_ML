# Titanic Survival Prediction - Machine Learning Project

## Overview
This project focuses on predicting passenger survival on the Titanic using Machine Learning techniques.  
It is based on the famous Kaggle competition **"Titanic: Machine Learning from Disaster"**, which is considered a classic beginner-to-intermediate ML problem.

The goal is to analyze passenger data and build models that can accurately predict whether a passenger survived or not.

---

## Dataset
The dataset includes information about passengers such as:
- Age
- Gender
- Ticket Class (Pclass)
- Fare
- Family relations (SibSp, Parch)
- Embarked port

Some features contain missing values, so preprocessing and feature engineering are essential steps.

---

## Project Workflow

### 1. Data Preprocessing
- Handling missing values (Age, Cabin, Embarked)
- Encoding categorical features (Sex, Embarked)
- Feature scaling (if needed)

### 2. Exploratory Data Analysis (EDA)
- Survival distribution
- Survival by gender, class, age
- Correlation between features

### 3. Feature Engineering
- Creating new features (e.g., Family Size)
- Extracting titles from names
- Transforming categorical data into numerical format

### 4. Model Building
Machine learning models used may include:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

### 5. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Cross-validation (optional)

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
