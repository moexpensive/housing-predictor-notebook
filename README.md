# California Housing Predictor - Notebook

This repository contains a Jupyter notebook that demonstrates the full data science workflow for predicting housing prices in California using the California Housing dataset.

## Contents

- `housing.ipynb` – The main notebook with:
  - Exploratory Data Analysis (EDA)
  - Feature engineering
  - Custom transformers and preprocessing pipelines
  - Model training and evaluation using Linear Regression, Decision Trees, Random Forests, and ensemble methods
- `housing.csv` – Dataset used in the notebook (optional if included)

## Overview

The notebook complements the deployed web application by showing:

1. How features are created, such as ratios of rooms and population per household.
2. Custom transformations like clustering for geographical features.
3. Model experimentation, including hyperparameter tuning with `GridSearchCV` and `RandomizedSearchCV`.
4. Final evaluation metrics to ensure models generalize well and avoid overfitting.

## How to Use

1. Clone this repository:

```bash
git clone https://github.com/moexpensive/housing-predictor-notebook.git
Open the notebook in Jupyter or VS Code:


Copy code
jupyter notebook housing.ipynb
Run the notebook cells step by step to explore the data, train models, and inspect results.

Notes
The final production model used in the deployed web app is in a separate repository.

This notebook is for educational and portfolio purposes.

License
MIT License
