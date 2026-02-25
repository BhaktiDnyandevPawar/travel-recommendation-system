# travel-recommendation-system
A Machine Learning-based travel recommendation system that predicts attraction ratings and provides personalized recommendations using regression, classification, and collaborative filtering techniques.

**Travel Recommendation System**
 Overview
The Travel Recommendation System is a Machine Learning project that predicts tourist attraction ratings and generates personalized recommendations using collaborative filtering techniques.

**This project demonstrates an end-to-end ML workflow including:**
Data Cleaning
Exploratory Data Analysis (EDA)
Regression Modeling
Classification Modeling
Recommendation System Implementation
Model Evaluation

 **Problem Statement**
1. Tourists often struggle to identify the best attractions based on personal preferences.
2.This system analyzes historical rating data to:
Predict attraction ratings
Classify rating categories
Recommend attractions based on user similarity

**Dataset Features**
User ID
Attraction ID
Category
Location
Rating (1–5 scale)
Target Variable: Rating

**Exploratory Data Analysis**
EDA included:
Rating distribution analysis
Category popularity analysis
Missing value handling
Feature encoding
Correlation analysis
The dataset showed class imbalance and subjective rating behavior.

 **Machine Learning Models**
**1.Regression – Rating Prediction**
Model Used: Gradient Boosting Regressor
Performance:
Mean Squared Error (MSE): 0.98
R² Score: 0.02
Cross-Validation R²: 0.02
The model performs better than a baseline predictor.
Low R² reflects the subjective nature of user ratings.

**2. Classification – Rating Category Prediction**
Multi-class classification model to predict rating classes.
Accuracy: 32%
Evaluation Metrics:
Precision
Recall
F1-Score
Confusion Matrix
Class imbalance was observed in the dataset.

**3. Recommendation System**
Implemented User-Based Collaborative Filtering:
Created user-item interaction matrix
Computed cosine similarity
Generated personalized recommendations
Sample Outputs
Confusion Matrix
Rating Distribution

**Technologies Used**
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

**Future Improvements**
Add sentiment analysis using review text
Implement matrix factorization (SVD)
Build hybrid recommendation system
Deploy using Streamlit

 Author
Name : Bhakti Pawar
