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

## Model Results
| Model |               Accuracy |          ROC-AUC  |

Logistic Regression      | 75.6% |          |0.7546 |
Random Forest            | 74.6% |          |0.7452 |
XGBoost                  | 75.3% |          |0.7524 |

## Key Finding
Carbohydrate intake was the most important predictor of glucose spikes.

## Tools Used
Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn
