# Student-Performance-Analysis
# Student Performance Classification

This project predicts whether a student will **pass or fail** based on their exam scores and other demographic features using **Logistic Regression**. It uses the StudentsPerformance.csv dataset.

## Project Structure

- StudentsPerformance.csv : Dataset  
- student_performance.ipynb : Main notebook with full workflow  
- README.md : Project documentation

## Problem Statement

Given the scores in Math, Reading, and Writing, along with demographic data (gender, parental education, etc.), the goal is to build a machine learning model that predicts if a student will pass (1) or fail (0).

## Pass/Fail Criteria

Students are classified as:  
- Pass (1) if their average score across the three subjects is ≥ 40  
- Fail (0) otherwise

## Steps Performed

1. Data Loading  
2. Data Cleaning & Preprocessing  
3. Feature Engineering – Added average score, target label (pass/fail)  
4. Label Encoding – Converted categorical features to numeric  
5. Model Building – Logistic Regression  
6. Model Evaluation – Accuracy, Confusion Matrix, F1 Score

## Features Used

- Gender  
- Race/Ethnicity  
- Parental level of education  
- Lunch type  
- Test preparation course  
- Math Score  
- Reading Score  
- Writing Score  

## Evaluation Metrics

- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)

## Requirements

Install the required libraries using:  
```bash
pip install -r requirements.txt

Future Work
Use Random Forest or XGBoost for better accuracy
Deploy the model with a Streamlit web app
Add more data visualizations and EDA insights

Acknowledgments
Dataset Source: Kaggle / UCI Machine Learning Repository
