# Salary-prediction-model
This project aims to build an accurate salary prediction system using machine learning models to estimate employee salaries based on multiple job-related factors. It leverages data preprocessing, feature engineering, and regression models to forecast salaries and help employers make data-driven compensation decisions.

📌 Objective
To predict employee salaries using machine learning algorithms by analyzing features such as:

Age

Gender

Education level

Job title

Years of experience

Experience-to-age ratio

🧠 Models Used
Linear Regression (baseline model)

Random Forest Regressor

XGBoost Regressor

⚙️ Methodology
Data Acquisition: Kaggle dataset with salary-related features.

Preprocessing: Handled missing values, encoded categorical features, and created the experience-to-age ratio.

Visualization: Used Seaborn & Matplotlib to analyze trends and relationships.

Modeling: Trained and evaluated models using RMSE, R², and prediction accuracy.

📈 Results
Random Forest achieved the highest accuracy of 91%, lowest RMSE of 12,735, and best R² score of 0.91.

XGBoost performed closely behind with 90% accuracy.

Linear Regression was less effective for capturing complex relationships.

✅ Key Features
Clean and scalable pipeline for salary prediction

Comparative analysis of model performances

Feature importance analysis for better HR decision-making

📊 Tools & Libraries
Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib, Seaborn

🔍 Use Cases
HR salary benchmarking

Candidate offer calibration

Labor market analysis
