# Lab 2 – Machine Learning with Scikit-Learn

## Overview
This lab demonstrates the complete Scikit-Learn workflow:
- Data loading and exploration
- Train/test split
- Model training (Decision Tree & KNN)
- Model evaluation
- Confusion matrix analysis
- Working with real-world CSV data

## Datasets Used
- Iris dataset (built-in sklearn dataset)
- Google Play Store dataset (googleplaystore.csv)

## Model Comparison (Google Play Dataset)

Decision Tree Accuracy: 72.65%  
KNN Accuracy: 75.75%

KNN performed better on the Google Play dataset. Since KNN uses distance-based learning and benefits from feature scaling, it captured patterns in numeric features more effectively than the Decision Tree. Therefore, KNN was selected as the preferred model for this dataset.

