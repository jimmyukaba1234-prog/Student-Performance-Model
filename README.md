Exam Score Prediction Using Machine Learning
Project Overview

This project focuses on predicting student exam scores using machine learning techniques. The model analyzes how academic engagement factors specifically hours studied and attendance rate — influence exam performance.

A linear regression model is trained to learn the relationship between these variables and generate accurate predictions. The project demonstrates the full data science workflow including data preprocessing, model training, evaluation, visualization, and interpretation.

Objectives:

- Understand the relationship between study habits and academic performance

- Build a predictive regression model

- Evaluate model accuracy and reliability

- Visualize predictions and residuals

- Demonstrate applied machine learning techniques

Dataset Description
The dataset contains the following features:

Feature	Description
Hours Studied	Number of hours a student spends studying
Attendance	Percentage or count of class attendance
Exam Score	Final exam score (target variable)

Technologies Used

- Python

- Pandas

- NumPy

- Matplotlib

- Scikit-learn


Project Workflow
1. Data Loading and Exploration

- Imported the dataset using Pandas

- Checked for missing values and data consistency

- Performed basic exploratory analysis

2. Feature Selection
Selected relevant predictors:

- Hours Studied

- Attendance

- Target variable:

- Exam Score

3. Data Splitting

Dataset split into:

- Training set

- Testing set

- Ensures unbiased evaluation and prevents overfitting


4. Model Training

- Implemented a Linear Regression model using Scikit-learn

- Trained the model on the training dataset
  

5. Model Evaluation

- Compared predicted values against actual exam scores

- Evaluated consistency between training and testing performance

- Analyzed residuals to assess model reliability and error distribution

6. Visualization

- Scatter plots showing relationships between variables
- Actual vs Predicted comparison plot
- Residual analysis plots

These visualizations help validate model performance and interpret trends.

Results:
- The model demonstrates a strong positive relationship between study habits and exam performance.

- Predictions closely match actual scores, indicating good learning accuracy.

- Residual analysis shows minimal bias and no significant overfitting.

- The model generalizes well to unseen data.

Potential Improvements
Add more features such as:

- Sleep hours
- Assignment completion rate
- Socio-economic factors
- Previous academic performance
- Try advanced models:
- Random Forest
- XGBoost
- Perform hyperparameter tuning
- Deploy as a web application or API
