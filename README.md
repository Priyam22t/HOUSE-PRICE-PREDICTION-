# 🏠 Boston House Price Prediction

## 📌 Project Overview
Boston House Price Prediction is a machine learning project that predicts the median value of houses based on socio-economic and geographical features. The project uses regression techniques to learn patterns between input features and house prices and evaluate model performance using standard metrics.

---

## 🎯 Problem Statement
To build a machine learning model that can accurately predict house prices using various factors such as crime rate, number of rooms, property tax, and accessibility to highways.

---

## 📊 Dataset Description
- **Dataset Name**: Boston Housing Dataset  
- **Source**: CMU StatLib  
- **Number of Features**: 13  
- **Target Variable**: Median value of owner-occupied homes (MEDV)

⚠️ Note: The `load_boston()` function has been deprecated in recent versions of scikit-learn. Therefore, the dataset is manually loaded from the original source and reconstructed in a scikit-learn compatible format.

---

## 🧾 Features
Some important features used in this project:
- CRIM – Crime rate per capita
- RM – Average number of rooms
- AGE – Proportion of old houses
- TAX – Property tax rate
- PTRATIO – Pupil-teacher ratio
- LSTAT – Percentage of lower-status population

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

---

## 🤖 Machine Learning Model
- **Model Used**: XGBoost Regressor  
- **Learning Type**: Supervised Learning  
- **Problem Type**: Regression  

XGBoost is chosen because it handles non-linear relationships well and provides better performance compared to traditional regression models.

---

## 🔄 Project Workflow
1. Load and preprocess the dataset  
2. Split data into training and testing sets  
3. Train the regression model  
4. Predict house prices  
5. Evaluate model performance  

---

## 📈 Model Evaluation
- **Metric Used**: R² Score  
- The model performance is evaluated by comparing actual house prices with predicted prices on both training and testing datasets.

---

## ▶️ How to Run the Project
1. Clone the repository  
2. Install the required dependencies  
   ```bash
   pip install -r requirements.txt
