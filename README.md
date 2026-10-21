# Lab 3: Regression Models for Ticket Resolution Time

**Name:** Mekdelawit Alemayehu
**ID:** UGR/9271/16

This lab compares a mean baseline, linear regression, polynomial regression (degree 2 and 3), Ridge and Lasso for predicting resolution_hours on a synthetic support ticket dataset. Models are compared with 5-fold cross-validation on the training set and reported with MAE, RMSE and R² on a held-out test set.

## Files

- lab3.ipynb: the notebook with code, plots, results and answers to the analysis questions
- lab_ticket_resolution.csv: the dataset

## Result

Linear regression on complexity_score and team_experience_years was chosen. On the test set it got MAE ≈ 2.9 h, RMSE ≈ 3.6 h and R² ≈ 0.88, compared with MAE ≈ 9.1 h for the mean baseline. lines_changed and reopened were left out because they are not known when a ticket is opened (leakage).

## How to run

Install numpy, pandas, matplotlib and scikit-learn, then open lab3.ipynb in Jupyter and run all cells.
