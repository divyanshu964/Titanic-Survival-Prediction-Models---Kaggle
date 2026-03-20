# Titanic-Survival-Prediction-Models---Kaggle
The objective of this project was to predict passenger survival on the Titanic using demographic and travel-related features. The goal was to identify key factors influencing survival and build a robust classification model to maximize prediction accuracy.

Data Analysis & Feature Engineering
1. Loaded and processed training and test datasets.
2. Converted categorical variables like Sex into numeric format using encoding.
3. Extracted titles from passenger names and transformed them into dummy variables to enhance predictive power.
4. Transformed Cabin values into unique numerical representations instead of creating high-dimensional dummy variables.
5. Dropped irrelevant columns like Name after extracting useful information.

Models Built
1. Logistic Regression (multiple variations with different feature sets)
2. K-Nearest Neighbors (tested across multiple values of K)
3. Random Forest Classifier (with different numbers of estimators such as 100 and 500)

Findings
1. Feature transformations such as gender encoding, title extraction, and cabin conversion improved model usability.
2. Multiple models were evaluated and compared based on prediction outputs.
3. Random Forest Classifier with 500 estimators achieved the highest accuracy of 78.22%, outperforming all other model variations and configurations in the notebook.
