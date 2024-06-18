# Automated Hyperparameter Optimization (HPO) System

## Overview
This project focuses on developing an automated hyperparameter optimization (HPO) system using AutoML techniques to efficiently identify the best hyperparameter configuration for given machine learning models and datasets. The system integrates with various machine learning models and handles different data types while employing optimization techniques like Bayesian optimization and TPE (Tree-Parzen Estimator).

## Features
- Supports multiple machine learning models.
- Handles different data types.
- Employs Bayesian Optimization and TPE for hyperparameter tuning.
- Compares performance using ROC AUC scores.
- Provides visualization for learning rate distribution curves.

## Requirements
- numpy
- pandas
- scikit-learn
- bayes_opt
- optuna
- matplotlib
    

## Usage
1. **Data Preprocessing**:
    The current implementation uses a synthetic dataset for demonstration.
    

2. **Model Evaluation**:
    Define a function to train and evaluate models using cross-validation and calculate ROC AUC.


3. **Hyperparameter Optimization**:
    Implement Bayesian Optimization and TPE to search for the best hyperparameter configuration.
    

4. **Comparison and Visualization**:
    Compare the performance of models with different optimization techniques and plot the results.
    

## Results
The system compares the performance of different optimization techniques and visualizes the ROC AUC scores. The results demonstrate the effectiveness of Bayesian Optimization and TPE in improving model performance compared to random search.
