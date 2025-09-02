**Overview**

This project predicts real estate prices in Bengaluru using machine learning models.
The dataset was taken from Kaggle
We perform data cleaning, feature engineering, visualization, and model training to build a predictive system for house prices.

**Dataset**

Source: Kaggle – Bengaluru House Price Dataset
Features: location, size, total_sqft, bath, price, etc.
Target Variable: price (in lakhs)

**Tech Stack**

Python
Libraries:
Data Processing → Pandas, NumPy
Visualization → Matplotlib, Seaborn
Machine Learning → Scikit-learn
Model Tuning → GridSearchCV, K-Fold Cross Validation

**Key Steps**

1. Data Cleaning
2. Feature Engineering
3. Data Visualization
4. Model Building using Linear Regression, Decision Tree Regresor, Lasso Regresor
   Used:
   K-Fold Cross Validation for robust evaluation
   GridSearchCV for hyperparameter tuning

**Results**

Model	               Accuracy
Linear Regression	   81.83%
Decision Tree	       72.31%
Lasso Regression	   68.74%

**How to Run**

1. Clone this repo:
   git clone https://github.com/jyotiitk/Real-Estate-House-Prediction/tree/main
   cd real-estate-price-prediction

2. Run the notebook:
   jupyter notebook main.ipynb

