# Thiranex Data Science Internship Projects

This repo contains my submissions for the Thiranex Data Science internship track, built using the Titanic passenger dataset.

## Project 1: Data Cleaning & Visualization
**File:** `Task1_Data_Cleaning_Visualization.ipynb`

Cleans a raw, messy dataset — handling missing values, duplicates, and outliers — then visualizes key insights using pandas, matplotlib, and seaborn.

**Key steps:** missing value imputation, duplicate removal, outlier capping (IQR method), and 5 visualizations covering survival patterns, age distribution, fare by class, and correlations.

## Project 2: Predictive Modeling Using Machine Learning
**File:** `Task2_Predictive_Modeling.ipynb`

Builds and evaluates classification models to predict passenger survival using the cleaned dataset from Project 1.

**Key steps:** trains Logistic Regression, Decision Tree, and Random Forest models; compares accuracy; visualizes performance with confusion matrices, ROC curves, and feature importance.

## Tech Stack
Python, pandas, numpy, matplotlib, seaborn, scikit-learn

## Folder Structure
├── Task1_Data_Cleaning_Visualization.ipynb
├── Task2_Predictive_Modeling.ipynb
├── titanic_raw.csv
├── titanic_cleaned.csv
└── plots/          # saved chart images from both notebooks
