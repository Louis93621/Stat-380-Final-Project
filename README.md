# Credit Card Approval Prediction (Stat 380 Final Project)

## Project Overview
This project aims to develop and evaluate predictive models to estimate the likelihood of credit card default using the "Default of Credit Card Clients" dataset from the UCI Machine Learning Repository. By analyzing demographic data and financial history, we identify key risk factors and compare multiple machine learning approaches.

## Authors
* **Ya-Nuo Hsu**
* **Ziyue Han**
* **Ruiyan Tang**
* *(Date: May 5, 2025)*

## Dataset
* **Source**: UCI Machine Learning Repository (Yeh & Lien, 2009)
* **Description**: 30,000 observations of Taiwanese credit card holders.
* **Features**: 24 variables including demographics (age, gender, education), credit limits, and 6 months of payment history.

## Methodology
We implemented and compared the following models:
1.  **Logistic Regression** (Baseline & Regularized with LASSO/Ridge)
2.  **Decision Tree** (CART)
3.  **Random Forest**
4.  **XGBoost**
5.  **Support Vector Machine (SVM)**
6.  **Neural Network**

## Key Findings
* [cite_start]**Best Performers**: **Random Forest** and **XGBoost** achieved the best balance of accuracy (~82%) and recall, effectively identifying potential defaulters[cite: 395, 413].
* [cite_start]**Critical Factor**: Recent payment status (PAY_0) was consistently identified as the strongest predictor of default across all models.

## Files
* `final_project.qmd`: The Quarto source file containing R code and analysis.
* `final_project.html`: The rendered report with full visualizations and results.

## How to Run
This project uses **R** and **Quarto**.
1.  Clone the repository.
2.  Open `final_project.qmd` in RStudio.
3.  Ensure required packages (tidyverse, caret, randomForest, xgboost, etc.) are installed.
4.  Render the file to generate the HTML report.
