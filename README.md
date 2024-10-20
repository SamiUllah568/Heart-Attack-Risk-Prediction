# Heart Attack Risk Prediction Project

## Overview

This project aims to predict the risk of heart disease in patients using a dataset containing various health-related features. By analyzing patient data, we can identify risk factors and provide insights into heart health, which may help in early detection and prevention of heart-related issues.

## Dataset

The dataset used in this project is the **"heart.csv"** file, which includes information about patients such as age, gender, blood pressure, cholesterol levels, and more. Below is a description of the features included in the dataset:

| Feature | Description |
|---------|-------------|
| **age** | The age of the patient (in years). |
| **sex** | Gender of the patient (0: female, 1: male). |
| **cp** | Type of chest pain experienced by the patient. (0: typical angina, 1: atypical angina, 2: non-anginal pain, 3: asymptomatic) |
| **trestbps** | Resting blood pressure (in mm Hg). |
| **chol** | Serum cholesterol level (in mg/dl). |
| **fbs** | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false). |
| **restecg** | Resting electrocardiographic results (0: normal, 1: ST-T wave abnormality, 2: left ventricular hypertrophy). |
| **thalach** | Maximum heart rate achieved. |
| **exang** | Exercise induced angina (1 = Yes, 0 = No). |
| **oldpeak** | ST depression induced by exercise relative to rest. |
| **Target** | Risk of heart attack (0 = less chance, 1 = more chance). |

## Objective

The primary objective of this project is to build a predictive model that can classify patients based on their risk of having a heart attack using machine learning algorithms. This project will help in understanding how different factors contribute to heart health.

## Tools and Libraries

The following tools and libraries are used in this project:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology

1. **Data Preprocessing**: Clean and preprocess the data, including handling missing values and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Visualize the data to understand the relationships between different features and the target variable.
3. **Model Building**: Use various machine learning algorithms (e.g., Logistic Regression, Random Forest, etc.) to train models on the training dataset.
4. **Model Evaluation**: Evaluate the models using metrics such as accuracy, precision, recall, and F1-score.

## Conclusion
This project demonstrates the application of data science and machine learning techniques to assess heart disease risk based on patient health data. It aims to contribute to the field of healthcare by providing tools for early detection and prevention strategies.
