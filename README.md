# 🏦 Bank Marketing Prediction - Logistic Regression

This project aims to predict whether a client will subscribe to a term deposit based on marketing campaign data. It demonstrates a complete Machine Learning pipeline applied to a financial business context.

## 📋 Project Overview
- **Objective:** Classify if a customer will say "Yes" or "No" to a bank offer.
- **Dataset:** Bank Marketing Dataset (contains features like age, job, marital status, and previous campaign outcomes).
- **Core Algorithm:** Logistic Regression.

## 🛠️ Key Technical Steps
1. **Data Preprocessing:** - Encoding categorical variables (Label Encoding).
    - Feature Scaling (StandardScaler) for better model performance.
2. **Model Training:** Splitting data into training and testing sets to ensure generalization.
3. **Advanced Evaluation:**
    - **ROC/AUC Curve:** To measure the model's ability to distinguish between classes.
    - **Confusion Matrix:** Visualizing True Positives vs. False Positives.
    - **Classification Report:** Detailed analysis of Precision, Recall, and F1-Score.
4. **Probability Analysis:** Exporting a comparison table showing the actual result vs. the model's prediction and the calculated probability.

## 🧪 Libraries Used
- **Pandas & Numpy:** Data cleaning and manipulation.
- **Scikit-Learn:** Machine Learning, scaling, and metrics.
- **Matplotlib & Seaborn:** Visualizing the ROC Curve and Confusion Matrix.

## 📊 Results
The model provides a clear probability score for each customer, allowing a bank to focus its marketing efforts on the leads most likely to convert.

---
*Developed as a practical application of supervised learning in the finance industry.*
