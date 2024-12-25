# Bayesian_Approach_IMF_Asylum

## Functionality:
**The goal of this project is to demonstrate to the curious person the basics of bayesian econometrics**, both conceptually and analytically, in a thematic jupyter notebook. We do this by explaining each step leading up to fitting various bayesian models. We try to elucidate the effect of IMF Loans on immigration, particularly asylum-seeking. The code is written in Python. We use PYMC3 for analysis.

**An extenstion of this project** is to use two ML techniques, LASSO and Random Forest, as LASSO accounts for multicollinearity and hence improves interpretability, and Random Forests generally improves prediction.

## Files:
bayesian_approach.ipynb is the core of this project, with step-by-step bayesian econometric analysis of the data. 
Random_Forests_IMF.ipynb & LASSO_IMF.ipynb are extension of this project using LASSO and Random Forest.
paper.pdf serves as a guide to IMF loans, immigration, and basic multiple linear regression models as it relates to IMF loans and immigration.
tables.pdf contains standard regression tables (created in STATA).
final_data.csv is the final dataset.
