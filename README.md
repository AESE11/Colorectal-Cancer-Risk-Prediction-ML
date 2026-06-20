Colorectal Cancer Risk Prediction using Machine Learning
Overview

This project aims to predict the risk of Colorectal Cancer (CRC) using machine learning techniques based on demographic, lifestyle, medical, and nutritional factors.

The workflow includes:

Data Cleaning
Missing Value Handling
Exploratory Data Analysis (EDA)
Feature Engineering
Data Preprocessing
Model Training
Model Evaluation
Ensemble Learning

The final objective is to classify individuals into:

High CRC Risk
Low CRC Risk
Dataset Description

The dataset contains health-related information about participants, including:

Feature	Description
Age	Participant age
Gender	Male/Female
BMI	Body Mass Index
Ethnicity	Ethnic background
Lifestyle	Lifestyle category
Family_History_CRC	Family history of colorectal cancer
Pre-existing Conditions	Existing medical conditions
Carbohydrates	Daily carbohydrate intake
Proteins	Daily protein intake
Fats	Daily fat intake
Vitamin A	Vitamin A intake
Vitamin C	Vitamin C intake
Iron	Iron intake
CRC_Risk	Target variable
Project Workflow
1. Data Cleaning
Removed unnecessary identifiers.
Handled missing values.
Corrected inconsistent categorical values.
Standardized text formatting.
2. Data Preprocessing
One-Hot Encoding for categorical features.
Feature Scaling using StandardScaler.
Target encoding.
3. Exploratory Data Analysis

Performed several analyses including:

Class distribution
Age vs CRC Risk
BMI distribution
Correlation Heatmap
Nutritional factor analysis
Machine Learning Models

The following models were trained and evaluated:

Logistic Regression

Used as a baseline classification model.

Random Forest Classifier

Used to capture non-linear relationships and feature interactions.

Voting Ensemble Classifier

Combined:

Logistic Regression
Random Forest

to improve prediction performance.

Evaluation Metrics

The models were evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn

Results

The ensemble model achieved the best overall performance and demonstrated better balance between precision and recall compared to individual models.

Future Improvements
Hyperparameter Tuning
Cross Validation
Feature Selection
XGBoost Implementation
Model Deployment using Streamlit
