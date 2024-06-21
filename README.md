# Bank Customer Churn Prediction Project

## Project Overview

The **Bank Customer Churn Prediction** project focuses on predicting customer churn in a bank setting. It involves analyzing various features like credit score, geography, gender, age, tenure, balance, number of products, credit card status, active membership, and estimated salary. The dataset utilized in this project comprises 10,000 rows and 13 columns.

## Project Phases

### 1. Data Cleaning and Preprocessing

- **Handling Missing Values**: Addressed any missing data points in the dataset.
- **Categorical Variable Encoding**: Converted categorical variables into a numerical format for analysis.
- **Feature Scaling**: Scaled features to bring them to a standard range.

### 2. Exploratory Data Analysis (EDA)

- **Insights and Distributions**: Explored the dataset to gain insights into feature distribution.
- **Correlation Analysis**: Examined the relationship between variables.
- **Visualizations**: Utilized visualizations such as count plots and correlation matrix heatmaps for better understanding.

### 3. Feature Engineering

- **New Feature Creation**: Introduced a new feature 'Zero Balance' derived from the balance feature.
- **Dummy Variables**: Used dummy variables to handle categorical variables effectively.

### 4. Model Building

- **Selection Process**: Employed various models like Logistic Regression, SVM, KNN, Decision Tree, Random Forest, Gradient Boosting, and XGBoost for predictions.
- **Performance Evaluation**: Assessed model performance based on metrics like Accuracy, Precision, Recall, and F1 Score.

### 5. Hyperparameter Tuning

- **Bayesian Optimization**: Optimized hyperparameters for **XGBoost** models to enhance predictive accuracy.

### 6. Results and Analysis

- **Model Performance**:
    - Random Forest and **XGBoost** outperformed other models with F1 Scores of 0.846 and 0.851, respectively.
- **Best Hyperparameters**:
    - Random Forest: {'max_depth': 2, 'n_estimators': 200}
    - XGBoost: {'max_depth': 6, 'n_estimators': 200}
- **Feature Importance**:
    - Key features driving predictions: 'Num Of Products', 'Balance', and 'Geography'.

## Conclusion and Recommendations

The Bank Customer Churn Prediction project effectively predicted customer churn using advanced machine learning techniques. Moving forward, potential enhancements could involve exploring additional features and fine-tuning models for even better accuracy.

## Future Work

Suggestions for future work include exploring more advanced algorithms and incorporating real-time data for dynamic predictions and improved customer retention strategies.


