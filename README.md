# Employee Promotion Prediction

## 📌 Overview
This repository contains a machine learning project aimed at predicting employee promotions at JMD Company. The model helps the HR team make data-driven decisions to streamline the promotion process.

## 🎯 Objective
To develop a machine learning model that predicts whether an employee is eligible for promotion based on historical data, reducing delays in the appraisal cycle.

## 📂 Dataset Description
The dataset includes employee records from the last appraisal cycle with the following features:

| Feature Name                | Description |
|-----------------------------|-------------|
| `employee_id`               | Unique identifier for the employee |
| `department`                | Department of the employee |
| `region`                    | Region of employment (unordered) |
| `education`                 | Education level |
| `gender`                    | Gender of the employee |
| `recruitment_channel`       | Channel through which the employee was recruited |
| `no_of_trainings`           | Number of trainings completed in the previous year (soft skills, technical skills, etc.) |
| `age`                       | Age of the employee |
| `previous_year_rating`      | Employee rating for the previous year |
| `length_of_service`         | Length of service in years |
| `awards_won`                | Whether the employee won any awards in the previous year (1 = Yes, 0 = No) |
| `avg_training_score`        | Average score in current training evaluations |
| `is_promoted`               | **Target Variable**: 1 if the employee is recommended for promotion, 0 otherwise |

## 🚀 Approach
1. **Data Preprocessing:** Handling missing values, encoding categorical variables, and normalizing numerical features.
2. **Exploratory Data Analysis (EDA):** Identifying patterns, trends, and correlations in employee promotions.
3. **Feature Engineering:** Creating new relevant features to improve model accuracy.
4. **Model Development:** Training multiple models (Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, XGBoost, etc.).
5. **Model Evaluation:** Using accuracy, precision, recall, F1-score, and ROC-AUC to select the best-performing model.
6. **Deployment (Optional):** Deploying the model with a user-friendly interface for HR personnel.

## 🛠 Technologies Used
- **Python**
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, XGBoost
- **Machine Learning Techniques:** Classification, Feature Engineering, Hyperparameter Tuning
