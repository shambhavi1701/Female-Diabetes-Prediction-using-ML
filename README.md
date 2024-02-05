# Female-Diabetes-Prediction-using-ML


## Overview
This GitHub repository contains a machine learning project for predicting diabetes in females using the Pima Indians Diabetes Database. The dataset is sourced from Kaggle and consists of various health-related features for female individuals. The goal of this project is to develop a predictive model that can identify the likelihood of diabetes based on these features.

## Dataset
The dataset used in this project is the Pima Indians Diabetes Database available on Kaggle. 
It includes the following features:
1. Pregnancies
2. Glucose
3. Blood Pressure
4. Skin Thickness
5. Insulin
6. BMI (Body Mass Index)
7. Diabetes Pedigree Function
8. Age
9. Outcome (0 or 1, indicating no diabetes or diabetes)

## Colab Notebook
You can access the Colab notebook by clicking the "Open In Colab" badge above.
## Notebook Contents

### 1. Importing the Dependencies

- Numpy, pandas, and scikit-learn are imported to handle data and build the machine learning model.

### 2. Data Collection and Analysis

- The diabetes dataset is loaded into a pandas DataFrame.
- Basic data analysis is performed, including displaying the first few rows, shape, and statistical measures.
- The distribution of outcomes (non-diabetic and diabetic) is explored.

### 3. Separating Features and Labels

- The dataset is divided into features (x) and labels (y).

### 4. Data Standardization

- StandardScaler is applied to standardize the feature data.

### 5. Data Train Test Splitting

- The dataset is split into training and testing sets.
