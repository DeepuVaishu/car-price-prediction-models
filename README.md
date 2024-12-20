# Car Pricing Prediction Project

## Problem Description
A Chinese automobile company is planning to enter the US market by establishing a local manufacturing unit. To gain a competitive edge, they need to understand the factors that influence car pricing in the American market, which may differ significantly from the Chinese market.

This project involves analyzing the factors affecting car prices and building predictive models to provide insights that will help the company design cars, devise business strategies, and set price levels for the US market.

## Business Goal
The objective is to develop a model to predict car prices based on various independent variables. The model will help:

1. Identify significant factors influencing car prices.
2. Provide actionable insights into pricing dynamics for the US market.

## Key Components

### 1. Loading and Preprocessing 
- Load the dataset and handle missing or inconsistent data.
- Perform exploratory data analysis (EDA) to understand the dataset's structure and relationships between variables.
- Apply necessary transformations such as encoding categorical variables, scaling numerical features, and splitting the dataset into training and testing sets.

### 2. Model Implementation 
Implement the following regression models:
1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **Gradient Boosting Regressor**
5. **Support Vector Regressor**

### 3. Model Evaluation 
Evaluate each model using the following metrics:
- **R-squared (R²)**
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**

Compare the models' performance and identify the best-performing model. Provide a clear justification for the choice.The Random Forest Regressor emerged as the best-performing model with the highest R-squared value of 0.520 and the lowest Mean Squared Error (MSE). This demonstrates its superior predictive capabilities for this dataset.

### 4. Feature Importance Analysis
Conduct feature selection to identify the significant variables affecting car prices. Use techniques such as:
- Feature importance scores from tree-based models
- Correlation analysis
- Recursive Feature Elimination (RFE)

## Deliverables
- **Code**: Provide a well-documented Jupyter Notebook containing the implementation.
- **Report**: Include concise explanations of the methodology, results, and conclusions.
- **Submission**: Share the GitHub repository link containing all files.

## Expected Outcomes
- A predictive model for car pricing with a detailed evaluation.
- Insights into key factors influencing car prices in the US market.
- Recommendations for the company to optimize their strategy for entering the US market.

---

## Repository Structure
```
|-- notebooks/
    |-- Machine Learning Project.ipynb
|-- README.md
```

## Acknowledgements
- Dataset provided by the automobile consulting firm.
- Tools and libraries used: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.

