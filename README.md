# Employee_attrition prediction
📌 Project Overview
Employee attrition — when employees leave an organization — can lead to significant costs in hiring, training, and lost productivity. This project uses machine learning to predict whether an employee is likely to leave based on HR and performance data.

The model not only predicts attrition but also identifies key factors influencing employee turnover and evaluates performance fairness across demographic groups such as gender and age.

🎯 Problem Statement
Develop an interpretable machine learning model to predict employee attrition using HR analytics data. The solution should identify key drivers behind attrition, evaluate fairness across demographic groups, and provide actionable insights to improve employee retention.

📊 Dataset
The dataset contains both categorical and numerical HR features, such as:

Demographics: Age, Gender, Marital Status

Job-related: Job Role, Job Level, Job Satisfaction, OverTime

Compensation: Monthly Income, Stock Option Level

Performance: Environment Satisfaction, Job Involvement

🛠 Approach
Data Cleaning & Preprocessing

Handled missing values

Encoded categorical variables

Scaled numerical features

Feature Selection

Identified most influential features using Random Forest feature importances

Model Development

Random Forest Classifier — for high accuracy and interpretability

Logistic Regression — as a simpler baseline model

Fairness Analysis

Evaluated precision, recall, and F1-score for different groups (e.g., Gender, Age Groups)

📈 Results
Random Forest Accuracy: ~85%

Top Influencing Features: OverTime, Marital Status, Job Satisfaction, Monthly Income, Age

Fairness analysis revealed performance variations across demographic groups, indicating areas for bias mitigation.

📌 Technologies Used
Python

Pandas, NumPy — Data processing

Scikit-learn — Machine learning models

Matplotlib, Seaborn — Data visualization

🚀 Future Improvements
Implement SHAP for advanced model interpretability

Tune hyperparameters for higher recall on attrition cases

Build an interactive Streamlit app for real-time predictions
