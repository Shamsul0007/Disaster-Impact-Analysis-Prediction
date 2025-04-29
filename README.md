# Disaster Impact Analysis and Prediction

## Overview
This project focuses on analyzing and predicting the impact of natural disasters using machine learning techniques. The dataset (`disaster_dataset.csv`) contains historical disaster data, including features like disaster type, region, year, magnitude, fatalities, affected population, economic loss, and severity level. The project includes exploratory data analysis (EDA), feature engineering, machine learning modeling for regression and classification tasks, and an interactive dashboard for predictions.

### Project Tasks
1. **Data Exploration (EDA)**:
   - Loaded and cleaned the dataset using Pandas.
   - Handled missing values, duplicates, and outliers.
   - Computed basic statistics and grouped data by `Disaster_Type` and `Region`.
   - Visualized distributions, frequencies, and correlations using Matplotlib and Seaborn.
2. **Feature Engineering**:
   - Applied feature encoding (Label Encoding and One-Hot Encoding) for categorical variables.
   - Analyzed feature importance for model optimization.
3. **Machine Learning Modeling**:
   - **Regression Task**: Predicted `Economic_Loss_USD_Million` using Linear Regression, Random Forest Regressor, and XGBoost Regressor.
   - **Classification Task**: Predicted `Severity_Level` using Random Forest Classifier and XGBoost Classifier.
   - Evaluated models using MAE, RMSE, R² Score for regression, and Accuracy, Precision, Recall, F1 Score, and Confusion Matrix for classification.
   - Performed hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
4. **Deployment**:
   - Built an interactive dashboard using Streamlit (`dashboard.py`).
   - Deployed the app on Streamlit Cloud (or provided instructions for deployment).

## Repository Structure
