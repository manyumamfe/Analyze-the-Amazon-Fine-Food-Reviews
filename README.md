# Analyze-the-Amazon-Fine-Food-Reviews
Analyze the Amazon Fine Food Reviews  and predict sentiments using various machine learning techniques, and Deep Learning
## Contents

- `amazone-fine-food-reviews (1).ipynb`: Jupyter notebook containing the analysis, data preprocessing, and machine learning model implementation.
- Python scripts and necessary files for running the analysis and models.

## Overview

### Objective
The goal is to analyze the Amazon Fine Food Reviews dataset, preprocess the data, and build machine learning models to classify and predict the review sentiments. The focus is on implementing Support Vector Machines (SVM) and optimizing the model using GridSearchCV.

### Key Components
1. **Data Loading and Preprocessing**:
    - Load the dataset.
    - Clean and preprocess the data for analysis.
  
2. **Exploratory Data Analysis (EDA)**:
    - Explore the data to understand its structure and key characteristics.
  
3. **Model Building**:
    - Build an SVM model with balanced class weights.
    - Implement cross-validation using `cross_validate`.
  
4. **Hyperparameter Tuning**:
    - Use GridSearchCV to find the best parameters for the SVM model.
  
5. **Results and Evaluation**:
    - Evaluate the model performance using accuracy and other relevant metrics.
