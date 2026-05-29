# AI-Powered Telecom Customer Churn Prediction and Retention Recommendation System

## Overview

Customer churn is one of the biggest challenges in the telecom industry because losing customers directly impacts revenue and business growth. This project develops an intelligent AI-powered system capable of predicting customer churn and generating personalized retention recommendations using machine learning techniques.

The system analyzes customer demographics, billing information, service subscriptions, and usage behavior to identify customers who are likely to leave the company. In addition, the project includes a recommendation engine that suggests suitable retention actions such as discounts, loyalty offers, contract upgrades, and customer support improvements.

---

## Problem Statement

Telecom companies face significant financial losses due to customer churn. Traditional systems often identify customer loss too late, making retention efforts less effective and more expensive.

This project aims to solve this problem by building an intelligent machine learning system that:

- Predicts customers likely to churn.
- Identifies the key factors contributing to churn.
- Provides personalized retention recommendations for high-risk customers.

---

## Project Objectives

- Analyze customer behavior and churn patterns.
- Identify the main factors affecting customer churn.
- Build and compare multiple machine learning models.
- Evaluate model performance using classification metrics.
- Develop a recommendation system for customer retention.
- Generate business insights to support decision-making.
- Deploy an AI-powered churn prediction system.

---

## Research Questions

- What percentage of customers churn?
- Which customer groups are more likely to churn?
- Does contract type affect churn?
- Is there a relationship between monthly charges and churn?
- Which telecom services are associated with higher churn?
- Which machine learning model performs best?
- What are the strongest predictors of churn?
- Which retention strategies are most effective for high-risk customers?

---

## Dataset

Dataset Used:
IBM Telco Customer Churn Dataset

Dataset Source:

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## Technologies Used

Programming Language

- Python

Data Analysis

- Pandas
- NumPy

Data Visualization

- Matplotlib
- Seaborn

Machine Learning

- Scikit-learn
- XGBoost

Imbalanced Data Handling

- SMOTE

Explainable AI

- SHAP

Deployment

- Streamlit

---

## Project Structure

telecom-customer-churn-prediction/

│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_preprocessing.ipynb
│   ├── 04_model_training.ipynb
│   ├── 05_model_evaluation.ipynb
│   └── 06_recommendation_system.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   ├── evaluate_model.py
│   ├── recommendation_engine.py
│   └── utils.py
│
├── models/
│
├── app/
│   └── streamlit_app.py
│
├── reports/
│
├── requirements.txt
├── README.md
└── .gitignore

---

## Project Workflow

Data Collection
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Handling Imbalanced Data
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Churn Prediction
       ↓
Retention Recommendation System
       ↓
Deployment

---

## Exploratory Data Analysis (EDA)

The project performs detailed exploratory analysis to answer important business questions such as:

- Churn distribution
- Contract type vs churn
- Monthly charges vs churn
- Tenure vs churn
- Internet services vs churn
- Payment methods vs churn

Visualizations include:

- Count plots
- Heatmaps
- Boxplots
- Histograms
- Correlation analysis

---

## Machine Learning Models

The following machine learning algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Recommendation System

The project includes a rule-based recommendation engine that generates personalized retention strategies for customers predicted to churn.

Example Recommendations

Customer Behavior| Recommended Action
High monthly charges| Offer discount
Month-to-month contract| Recommend yearly contract
New customer| Provide welcome package
Frequent support issues| Priority customer support
High churn probability| Immediate retention campaign

---

## Deployment

The final system can be deployed using Streamlit to provide:

- Real-time churn prediction
- Customer risk analysis
- Retention recommendations
- Interactive dashboard

---

## Expected Results

- Improved churn prediction accuracy
- Better customer retention strategies
- Reduced revenue loss
- Business-driven AI insights

---

## Future Improvements

- Deep Learning implementation
- Real-time telecom analytics
- Customer segmentation integration
- Reinforcement learning recommendations
- Cloud deployment
- Automated retraining pipeline

---

## Author

Mohammed Alnoor Salama Abdallah

- Computer Science Student
- Data Science & Machine Learning Enthusiast

LinkedIn:
https://www.linkedin.com/in/mohammed-alnoor-338550241

