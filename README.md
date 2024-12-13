Bank Marketing Campaign Analysis and Prediction
Overview
This project analyzes a bank marketing dataset to predict customer responses to marketing campaigns using machine learning. It involves data preprocessing, exploratory data analysis (EDA), and the implementation of multiple machine learning models to derive actionable insights.

Dataset
Source: Bank Marketing Dataset
Size: 41,188 rows and 21 columns
Key Features:
age, job, marital, education, and default (demographics)
duration, campaign, pdays, previous (campaign-related features)
y (target variable indicating whether the client subscribed to a term deposit)
Steps Performed
Data Preprocessing:

Handled missing values and outliers.
Encoded categorical variables.
Normalized numerical features.
Exploratory Data Analysis (EDA):

Identified correlations between features using heatmaps.
Visualized data distributions and campaign outcomes.
Machine Learning Models:

Logistic Regression
Naive Bayes
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
XGBoost
Evaluation Metrics:

Accuracy, Precision, Recall, F1 Score.
Confusion matrices for detailed performance analysis.
Results
Best Model: XGBoost
Accuracy: 91%
Precision: 64%
Recall: 54%
F1 Score: 58%
Key Insights
Feature duration was highly influential in determining campaign success.
XGBoost outperformed other models in balancing precision and recall.
Effective preprocessing and feature selection significantly enhanced model performance.
