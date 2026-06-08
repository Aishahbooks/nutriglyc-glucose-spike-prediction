# Glucose Spike Prediction - NutriGlyc AI Solutions

## Project Overview
This project builds a predictive analytics pipeline to detect glucose spikes in diabetes patients using machine learning. It was developed as part of an AI-driven nutrition solution for early detection and management of Type 2 Diabetes.

## Dataset
- 5,000 patient records with 28 features
- Target variable: glucose_spike (0 = No Spike, 1 = Spike)
- Features include: carbohydrate intake, BMI, pre-meal glucose, physical activity, sleep hours, stress level and more

## Project Pipeline
- Data Cleaning (missing values, duplicates, data types)
- Exploratory Data Analysis (7 visualisations with insights)
- Feature Engineering (3 new features, encoding, scaling)
- Model Development (Logistic Regression, Random Forest, XGBoost)
- Model Evaluation (Accuracy, Precision, Recall, F1-Score, ROC-AUC)
- Feature Importance Analysis

## EDA Highlights

### Glucose Spike Distribution
![Glucose Spike Distribution](Glucose%20Spike%20Distribution.png)

### Carbohydrate Intake vs Glucose Spike
![Carb Intake vs Glucose Spike](Carb%20Intake%20vs%20Glucose%20Spike.png)

## Model Results

### Performance Comparison
![Model Comparison](Model%20Comparison%20table.png)

### ROC Curves
![ROC Curves](ROC%20Curve.png)

## Key Risk Factors

### Feature Importance
![Feature Importance](Features%20Importance.png)

## Key Finding
Carbohydrate intake was the most important predictor of glucose spikes, followed by insulin dose and physical activity.

## Tools Used
Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

## Repository
[View Full Notebook](diabetes_analysis.ipynb)
