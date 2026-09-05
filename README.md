# Predictive Analytics

A portfolio of supervised machine learning projects covering classification and regression — model building, evaluation, and comparison across a range of real-world datasets.

## Overview

This repository focuses on predictive modelling: given historical, labeled data, train and evaluate models that predict an outcome — a category (classification) or a continuous value (regression) — on new data. It's the predictive counterpart to [Descriptive-Analytics](https://github.com/Praveen-Reddy74/Descriptive-Analytics), which covers dashboard-based analysis of historical data.

## ML Classification

8 projects applying classification techniques (including logistic regression, decision trees, and model comparison workflows) to problems such as absenteeism-risk categorization, cardiovascular risk prediction, insurance fraud/claim classification, employee promotion prediction, diabetes onset prediction, survival prediction, vehicle transmission-type prediction, and wine quality classification.

## ML Regression

2 projects applying regression techniques, including ensemble regression methods, to bike-sharing demand prediction and house price prediction.

## Portfolio Projects

| Project | Category | Focus |
|---|---|---|
| [Absenteeism](./ML_Classification/Absenteeism) | Classification | Categorizing employee absenteeism (Low/Medium/High) from demographic, lifestyle, and work-related data using logistic regression and decision trees |
| [CHD patients Classification](./ML_Classification/CHD%20patients%20Classification) | Classification | Predicting long-term coronary heart disease risk from clinical and lifestyle indicators |
| [Classifying valid Insurance claim[Fraud or not]](<./ML_Classification/Classifying valid Insurance claim[Fraud or not]>) | Classification | Detecting/predicting insurance claim outcomes from customer and policy attributes |
| [HR Promotion Prediction](./ML_Classification/HR%20Promotion%20Prediction) | Classification | Predicting employee promotion outcomes from HR data |
| [PIMA Indians Diabetes](./ML_Classification/PIMA%20Indians%20Diabetes) | Classification | Predicting diabetes onset from diagnostic measurements, comparing multiple models |
| [Titanic Survival](./ML_Classification/Titanic%20Survival) | Classification | Predicting passenger survival on the Titanic dataset |
| [Toyota Transmission Classification](./ML_Classification/Toyota%20Transmission%20Classification) | Classification | Predicting vehicle transmission type (Automatic/Manual) from vehicle specifications |
| [Wine Quality Prediction](./ML_Classification/Wine%20Quality%20Prediction) | Classification | Predicting wine quality from physicochemical measurements |
| [Bike Sharing Demand Prediction](<./ML_Regression/Bike Sharing Demand Prediction>) | Regression | Predicting bike rental demand using individual and ensemble regression models |
| [Boston Housing Prices](./ML_Regression/Boston%20Housing%20Prices) | Regression | Predicting house prices from the Boston Housing dataset |

Each project folder has its own README with further detail; some also include Jupyter notebooks, raw datasets, and result outputs.

## Technology Stack

Python, Jupyter Notebook, and the standard Python ML stack (pandas, scikit-learn, and related libraries used across the notebooks). Specific techniques used across projects include logistic regression, decision trees, and ensemble regression methods.

## Repository Structure

```
Predictive-Analytics/
├── README.md
├── .gitignore
├── ML_Classification/
│   ├── README.md
│   ├── Absenteeism/
│   ├── CHD patients Classification/
│   ├── Classifying valid Insurance claim[Fraud or not]/
│   ├── HR Promotion Prediction/
│   ├── PIMA Indians Diabetes/
│   ├── Titanic Survival/
│   ├── Toyota Transmission Classification/
│   └── Wine Quality Prediction/
└── ML_Regression/
    ├── README.md
    ├── Bike Sharing Demand Prediction/
    └── Boston Housing Prices/
```

## How to Explore

Each project folder contains its own README, dataset(s), and notebook(s) — open the relevant `.ipynb` in Jupyter to see the data preparation, modelling, and evaluation steps for that project.

## Skills Demonstrated

Supervised classification and regression, exploratory data analysis and feature engineering, model evaluation (accuracy, confusion matrices, cross-validation), decision tree and ensemble methods, and comparative model evaluation across multiple algorithms.
