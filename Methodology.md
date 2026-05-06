# Methodology

## Data Processing

The framework applies a structured preprocessing workflow including:

- Missing value handling
- Numerical scaling
- Temporal encoding
- Feature transformation
- Data validation

---

## Feature Engineering

Several engineered variables are generated to improve model performance:

- Degree-day indicators
- Rolling averages
- Temporal variables
- Weather interaction features

---

## Model Training

The following models are evaluated:

- Linear Regression
- Ridge Regression
- LASSO
- Random Forest
- XGBoost
- CatBoost

Cross-validation and hyperparameter optimization are applied to improve robustness and generalization.

---

## Evaluation Metrics

Performance is evaluated using:

- MAE
- RMSE
- R² Score

---

## Objective

The primary objective is to investigate how multidimensional environmental variables and machine learning methods can improve building energy forecasting performance compared to traditional temperature-based approaches.
