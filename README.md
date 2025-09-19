# Dementia Classification using Machine Learning

## Overview
This project implements and evaluates machine learning models to classify dementia status using clinical and neuroimaging data from the OASIS Longitudinal Demographics dataset. Two supervised learning algorithms, Logistic Regression and Support Vector Machines (SVM) with an RBF kernel, are applied. The goal is to develop automated tools that support early and accurate dementia diagnosis.

## Project Contents
- **APR_Assignment_1.ipynb**: Jupyter notebook containing the complete implementation, including data preprocessing, model training, hyperparameter tuning, evaluation, and visualization.
- **OASIS Longitudinal Demographics Dataset**: The dataset used, containing demographic, cognitive, and brain imaging features.
- **APR_Assignment_1_report.pdf**: A detailed project report covering theory, methodology, results, and discussion of the models.

## Features and Methods
- Data preprocessing involves encoding categorical variables, median imputation for missing SES values, and standard scaling.
- Logistic Regression and SVM classifiers are trained and evaluated using an 80-20 train-test split.
- Hyperparameter tuning via Grid Search is conducted for SVM to optimize model parameters.
- Principal Component Analysis (PCA) reduces feature dimensionality for visualization of model decision boundaries.
- Performance metrics include precision, recall, F1-score, and accuracy, with comparisons visualized through bar charts.

## How to Run
1. Ensure all dependencies are installed: Python 3.x, scikit-learn, matplotlib, numpy, pandas.
2. Load the OASIS dataset in the notebook environment.
3. Execute cells sequentially in `APR_Assignment_1.ipynb` to preprocess data, train models, tune hyperparameters, evaluate, and visualize results.
4. View the report (`APR_Assignment_1_report.pdf`) for detailed explanations and analysis.

## Results Summary
- Both Logistic Regression and SVM achieve high accuracy in dementia classification.
- SVM shows slightly better precision and recall, especially on the demented class.
- PCA effectively visualizes the decision boundary in 2D space.
- Plots comparing classifier performance metrics provide intuitive insights on model strengths.
