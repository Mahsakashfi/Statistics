# Week 2 — Multiple Linear Regression

## Objective
The goal of this week is to extend simple linear regression to a multiple linear regression setting and to understand how regression behaves when several predictors are included simultaneously.

The focus is on **interpretation and diagnostics**, not on model optimization.

---

## Dataset
- **California Housing Dataset**
- Target variable: `median_house_value`
- Predictors include demographic, geographic, and housing structure variables.

---

## What Is Covered in This Notebook

### 1. Exploratory Data Analysis (EDA)
- Inspection of variable distributions
- Identification of potential relationships and scale differences
- Handling of missing values

### 2. Feature Engineering
- Creation of ratio variables such as:
  - rooms per household
  - population per household
  - bedrooms per room
- One-hot encoding of categorical features

### 3. Multiple Linear Regression
- Fitting an Ordinary Least Squares (OLS) regression model
- Interpretation of coefficients as conditional effects
- Discussion of sign vs magnitude of coefficients

### 4. Multicollinearity Analysis
- Computation of Variance Inflation Factor (VIF)
- Identification of severe multicollinearity, especially among spatial and housing-related variables
- Explanation of how multicollinearity affects coefficient stability but not predictive performance

### 5. Model Evaluation
- Train–test split to assess generalization
- Evaluation using R², adjusted R², and RMSE
- Comparison of full and reduced models to illustrate redundancy among predictors

---

## Key Takeaways
- In multiple regression, coefficients represent effects **holding other variables constant**
- High multicollinearity limits interpretability but does not necessarily harm prediction
- Predictive performance should be evaluated separately from coefficient stability
- Real-world datasets often violate ideal conditions, and diagnosing these issues is part of the modeling process

---

## Next Step
Week 3 will focus on **regression assumptions and diagnostics**, including residual analysis, heteroscedasticity, normality, and influence measures.
