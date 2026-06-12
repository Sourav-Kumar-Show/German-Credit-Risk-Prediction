# German Credit Risk Prediction

## Overview

This project predicts whether a loan applicant is a **Good Credit Risk** or **Bad Credit Risk** using machine learning.

The project covers the complete workflow from data cleaning and exploratory data analysis (EDA) to model training, evaluation, and deployment through a Streamlit web application.

## Dataset

The project uses the **German Credit Risk Dataset**, which contains customer demographic and financial information.

### Features

* Age
* Sex
* Housing
* Saving Accounts
* Checking Account
* Credit Amount
* Duration

### Target

* Good Credit Risk
* Bad Credit Risk

## What I Did

* Cleaned and prepared the dataset
* Handled missing values
* Performed Exploratory Data Analysis (EDA)
* Created visualizations to understand patterns and risk factors
* Encoded categorical features
* Trained multiple machine learning models
* Tuned model parameters using GridSearchCV
* Compared model performance
* Selected the best-performing model
* Saved the trained model and encoders using Joblib
* Built a Streamlit web application for real-time predictions

## Exploratory Data Analysis

The analysis included:

* Histograms
* Box Plots
* Count Plots
* Scatter Plots
* KDE Plots
* Violin Plots
* Correlation Analysis
* Risk Distribution Analysis

## Models Used

* Decision Tree Classifier
* Random Forest Classifier
* Extra Trees Classifier
* XGBoost Classifier

### Final Selected Model

**Extra Trees Classifier**

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Streamlit
* Joblib

## Web Application

The Streamlit application allows users to enter applicant details and instantly predict credit risk.

### Input Features

* Age
* Sex
* Housing
* Saving Accounts
* Checking Account
* Credit Amount
* Duration

### Prediction Output

* GOOD Credit Risk
* BAD Credit Risk

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Machine Learning
* Classification
* Hyperparameter Tuning
* Model Evaluation
* Model Deployment

## Repository Structure

```text
├── analysis_model.ipynb
├── app.py
├── extra_trees_credit_model.pkl
├── *_encoder.pkl
├── README.md
```

## Future Improvements

* Probability-based risk prediction
* Model explainability using SHAP
* Interactive dashboard
* Cloud deployment

## Author

**Sourav Kumar**

Data Analyst | Data Science Enthusiast
