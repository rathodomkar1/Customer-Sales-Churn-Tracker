# Customer Sales & Churn Tracker

# Overview
This project performs an end-to-end data analysis on retail transactions. The goal was to identify customer segments through RFM (Recency, Frequency, Monetary) analysis and predict potential churn to improve customer retention strategies.

# Key Technical Steps
Data Preprocessing:Handled missing values and identified returned orders to clean the dataset.
RFM Segmentation: Engineered features to categorize customers by value and engagement.
Predictive Modeling: Trained a balanced `RandomForestClassifier` to identify churn-risk customers.

# Model Performance
Overall Accuracy:71%

F1-Score (Churners): 0.59

The model was tuned with balanced class weights to address data imbalance.*

# Technologies Used
- Python (Pandas, Scikit-Learn, Seaborn)
- Jupyter Notebooks
- Git/GitHub
