# ML Project

## Abstract
[Abstract.pdf](./docs/Abstract.pdf)

## Description
Developed machine learning models to predict 30-day readmissions for diabetes patients using a dataset from 130 U.S. hospitals (1999–2008) with 101,766 records and 48 features. Conducted thorough exploratory data analysis, feature engineering, and data cleaning to enhance model performance.

Key techniques:
- Encoding categorical variables, handling missing values, and reducing irrelevant or noisy features.
- Applied models like Decision Tree, Random Forest, Gradient Boosting, GaussianNB, XGBoost, and Logistic Regression, with SMOTE to address class imbalance.
- Hyperparameter tuning using `RandomizedSearchCV` and `GridSearchCV`.

Highlighted techniques:
- **Evaluation Metrics:** Recall and F1-score for identifying minority class.
- **Explainability:** SHAP values to improve model transparency.

This project showcases the transformative potential of predictive analytics in healthcare, enabling proactive interventions and reducing readmission rates.

## Contents
- `notebooks/`: Contains the Jupyter notebook with the code implementation.
- `docs/`: Contains the abstract and the report.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ML_project.git
