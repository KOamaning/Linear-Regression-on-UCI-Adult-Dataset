# Linear-Regression-on-UCI-Adult-Dataset

This notebook explores a linear regression approach to predict the number of hours a person works per week based on their age and education level.

# Features Used:
- Age
- Education level (`education-num`)

# Target:
- Weekly work hours (`hours-per-week`)

# Workflow:
1. Data is split into 50% training and 50% test sets.
2. An OLS linear regression model is fit to the training data.
3. Coefficients and model statistics (standard error, adjusted R²) are interpreted.
4. The model is evaluated using Mean Absolute Error (MAE) compared against a baseline average model.



Used Python libraries: `pandas`, `numpy`, `statsmodels`, `sklearn`
