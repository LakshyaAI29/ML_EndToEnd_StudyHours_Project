# ML_EndToEnd_StudyHours_Project
End-to-end Machine Learning project demonstrating data cleaning, preprocessing, encoding, feature scaling, train-test split, and model training using Linear Regression to predict student test scores.

# Customer Data ML Workflow

This project demonstrates an end-to-end Machine Learning workflow on a customer dataset.

## Project Overview
- End-to-end ML workflow from raw data to model-ready dataset.
- Dataset contains customer information including Age, Gender, City, Annual Income, Signup Date, Feedback Score, and Purchased status.
- Focus on *data cleaning, preprocessing, encoding, scaling, and train-test split*.

## Features
- *Data Cleaning:* Handles missing values in Age, Gender, Annual_Income, and Feedback_Score.
- *Encoding:* 
  - Label Encoding for binary categorical variables (Gender, Purchased).
  - One-Hot Encoding for multi-class categorical variables (City).
- *Feature Scaling:* Standardization of numeric features to improve model performance.
- *Train-Test Split:* Only target variable is separated for model training/testing.

## Dataset
- 20 customer records with 8 features including numerical and categorical data.
- Contains missing values which are handled during preprocessing.
- Target variable can be Purchased for classification or Feedback_Score for regression.

## Installation
1. Clone the repository:
