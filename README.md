# Lung Cancer Prediction Project

## Overview
This project implements machine learning models to predict lung cancer based on patient health data. It includes data preprocessing, exploratory analysis, and the implementation of several classification algorithms.

## Features
- Data preprocessing and encoding
- Exploratory data analysis
- Multiple machine learning models:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Support Vector Machine (SVM)
  - Naive Bayes
  - Random Forest (Ensemble)
- Model evaluation metrics:
  - Accuracy scores
  - Confusion matrices
  - Precision, Recall, and F1 scores

## Dataset
The dataset contains 309 patient records with 16 features including:
- Demographic information (Gender, Age)
- Lifestyle factors (Smoking, Alcohol consumption)
- Symptoms (Yellow fingers, Anxiety, Fatigue, etc.)
- Medical history (Chronic disease, Allergy)
  
**Target variable:** Lung Cancer (YES/NO)

## Models Performance Summary
| Model                | Accuracy | Precision       | Recall          | F1 Score        |
|----------------------|----------|-----------------|-----------------|-----------------|
| Logistic Regression  | 91.26%   | [91.49%, 88.89%] | [98.85%, 50.00%] | [95.03%, 64.00%] |
| KNN                  | 85.44%   | [87.50%, 57.14%] | [96.55%, 25.00%] | [91.80%, 34.78%] |
| Decision Tree        | 85.44%   | [87.50%, 57.14%] | [96.55%, 25.00%] | [91.80%, 34.78%] |
| SVM                  | 84.47%   | [84.47%, 0%]     | [100%, 0%]       | [91.58%, 0%]     |
| Naive Bayes          | 86.41%   | [89.25%, 60.00%] | [95.40%, 37.50%] | [92.22%, 46.15%] |
| Random Forest        | 90.29%   | [91.40%, 80.00%] | [97.70%, 50.00%] | [94.44%, 61.54%] |

## Requirements
- Python 3.7+
- Jupyter Notebook

## Required Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Results
The Logistic Regression model achieved the highest accuracy of 91.26%, while Random Forest also performed well with 90.29% accuracy. Detailed performance metrics for each model are available in the notebook.
