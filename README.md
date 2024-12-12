# Rainfall-Prediction-ML
This repository contains a machine learning pipeline for predicting rainfall based on meteorological data. The project uses two classification models, XGBoost and Logistic Regression, to identify whether rainfall will occur (yes or no). The dataset, preprocessing steps, and model evaluations are documented to ensure reproducibility and transparency.
Features

    Dataset: Includes meteorological features such as wind direction, wind speed, and other climate indicators.
    Data Preprocessing:
        Missing values imputed with feature means.
        Class imbalance addressed through minority class upsampling.
        Correlation analysis to understand feature relationships.
    Models:
        XGBoost Classifier: A powerful gradient boosting algorithm for structured data.
        Logistic Regression: A baseline statistical model for binary classification.
    Evaluation Metrics:
        Accuracy
        Precision, Recall, F1-score (via Classification Report)
        Confusion Matrix

Project Workflow

    Data Exploration:
        Understand the dataset structure and statistical properties.
        Visualize correlations and class distributions.
    Preprocessing:
        Handle missing values and encode target labels.
        Balance classes using upsampling techniques.
    Modeling:
        Train-test split (80%-20%).
        Train and evaluate XGBoost and Logistic Regression models.
    Performance Evaluation:
        Compare models using standard metrics.

Visualizations

    Correlation Heatmap: Illustrates relationships between features.
    Count Plots and Box Plots: Depict class distributions and feature behaviors.

Results

Both models demonstrated effective performance in predicting rainfall. XGBoost achieved higher accuracy and recall, making it better suited for this application.
