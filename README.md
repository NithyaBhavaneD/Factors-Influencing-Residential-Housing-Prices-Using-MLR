# Housing Price Analysis Using Multiple Linear Regression

## Overview

This project analyzes the factors influencing residential housing prices using **Exploratory Data Analysis (EDA)** and **Multiple Linear Regression (MLR)**.

The analysis aims to identify which property characteristics are associated with housing prices and translate the statistical findings into practical insights for buyers, sellers, and real-estate agents.

## Dataset

The dataset was obtained from **Kaggle** and contains:

* **545 residential property records**
* **13 attributes**
* Target variable: **Price**
* Numerical, binary, and categorical features
* No missing or duplicate values

Key variables include **area, bedrooms, bathrooms, stories, parking, air conditioning, basement, main road access, preferred area, and furnishing status**.

## Analysis Performed

The project follows these main steps:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Descriptive statistics and visualizations
* Correlation analysis
* Multiple Linear Regression
* Multicollinearity diagnosis using **Variance Inflation Factor (VIF)**
* Feature removal to address multicollinearity
* Ridge Regression as a robustness check
* Model evaluation using R², Adjusted R², MAE, and RMSE
* Interpretation of significant predictors and business implications

## Key Findings

The final MLR model achieved:

| Metric      |     Result |
| ----------- | ---------: |
| Train R²    |      0.685 |
| Adjusted R² |      0.676 |
| Test R²     |      0.650 |
| Test MAE    |   ₹977,502 |
| Test RMSE   | ₹1,329,747 |

The analysis found that **bathrooms, air conditioning, hot-water heating, preferred area, stories, basement, main road access, parking, and area** had statistically significant positive associations with housing price.

**Guestroom** was not statistically significant in the final model.

Multicollinearity was identified among several structural variables. **Bedrooms**, which had a VIF of 17.26 in the initial model, was removed. This resulted in similar predictive performance while reducing the multicollinearity issue.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Scikit-learn
* Jupyter Notebook / Google Colab


## Project Files

* **Notebook:** Contains the complete Python-based data analysis and modelling workflow.
* **Dataset:** Original Kaggle housing dataset used for the analysis.
* **Report:** Detailed explanation of the methodology, statistical analysis, findings, and business insights.

## Dataset Source

The dataset was sourced from **Kaggle**.

Kaggle profile: https://www.kaggle.com/nithyabhavanerajan

## Author

**Nithya Bhavane D**

*Predictive Analytics & Data Storytelling Project*
