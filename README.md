# VSNeoBank Customer Attrition Analysis

## Introduction
This repository contains a machine learning project aimed at analyzing customer data from VSNeoBank, a digital-only banking platform, to understand customer behavior and improve customer retention. The provided dataset includes information about customers and their transactions. The goal is to develop machine learning models to identify factors contributing to customer attrition and provide actionable recommendations to enhance the customer experience.

## Background
VSNeoBank is a digital-only banking platform headquartered in Melbourne, Victoria, providing banking services exclusively online to customers across Australia. With the recent observation of increased customer attrition rates, the company aims to delve into their business data to gain insights into customer behavior and improve retention strategies.

## Dataset
The dataset used in this project is provided in two files:
- `VSNeoBank.csv`: Dataset containing customer and transaction information.
- `VSNeoBank_deploy.csv`: Unlabeled dataset for model deployment and evaluation.

## Specific Requirements
### Part A: Machine Learning Findings Report 
This report should include:
- Dataset exploration approach
- Machine learning techniques utilized
- Findings supported by relevant visualizations and statistical analysis

### Part B: Consultancy Report f
This report should provide:
- Summary of findings
- Key insights from machine learning analysis
- Actionable recommendations to improve customer experience and retention
- Discussion on limitations and potential areas for future improvements

## Project Structure
- `VSNeoBank.csv`: Dataset containing customer and transaction details.
- `VSNeoBank_deploy.csv`: Unlabeled dataset for model deployment.
- `data_analysis.ipynb`: Jupyter Notebook containing data exploration, preprocessing, model development, and evaluation.
- `model.pkl`: Serialized machine learning model for deployment.
- `Part_A_Report.pdf`: Machine learning findings report 
- `Part_B_Report.pdf`: Consultancy report
- `README.md`: Markdown file providing an overview of the project.

## Approach
1. **Data Exploration**: Analyze the dataset to understand customer demographics, transaction patterns, and churn behavior.
2. **Data Preprocessing**: Clean the data, handle missing values, encode categorical variables, and prepare features for modeling.
3. **Model Development**: Develop machine learning models (e.g., logistic regression, decision trees, random forests) to predict customer attrition.
4. **Model Evaluation**: Evaluate the models using appropriate metrics (e.g., accuracy, precision, recall) and select the best-performing one.
5. **Consultancy Report**: Summarize findings, provide insights, and offer actionable recommendations to improve customer experience and retention.

## Dependencies
- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

## Results
The final model achieved an accuracy of 0.96 on the test dataset. Actionable recommendations for improving customer experience and retention are provided in the consultancy report.
