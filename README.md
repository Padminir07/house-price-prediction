# 🏠 House Price Prediction using Machine Learning

## 📌 Problem Statement
The objective of this project is to predict house prices based on various features such as square footage, number of bedrooms, bathrooms, lot size, and other factors using regression techniques.

---

## 🎯 Objectives
- Perform data preprocessing (handling missing values, duplicates, outliers)
- Conduct Exploratory Data Analysis (EDA)
- Apply feature engineering techniques
- Train regression models
- Evaluate and compare model performance

---

## 📂 Dataset Description
The dataset contains the following features:

- square_footage  
- num_bedrooms  
- num_bathrooms  
- year_built  
- lot_size  
- garage_size  
- neighborhood_quality  
- house_price (target variable)

---

## 🔍 Data Preprocessing
- Checked for missing values and handled them  
- Removed duplicate records  
- Converted column names to lowercase  
- Applied log transformation to reduce skewness  
- Removed outliers using IQR method  

---

## 📊 Exploratory Data Analysis
- Histograms to understand data distribution  
- Scatter plot to analyze relationship between features and target  
- Correlation heatmap to identify important features  

---

## 🤖 Models Used
- Linear Regression  
- K-Nearest Neighbors (KNN) Regression  

---

## 📈 Evaluation Metrics
- MAE (Mean Absolute Error)  
- MSE (Mean Squared Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  

---

## 🆚 Model Comparison

- Linear Regression achieved lower error values (MAE, RMSE)
- Linear Regression had higher R² score (~0.937)
- KNN showed comparatively lower performance

### ✅ Conclusion:
Linear Regression performed better because it provides more accurate predictions and fits the linear relationship in the dataset effectively.

---

## 🚀 Future Improvements
- Use advanced models like Random Forest and Gradient Boosting  
- Perform hyperparameter tuning  
- Add more relevant features  

---

## 🔗 GitHub Repository
https://github.com/Padmini07/house-price-prediction
