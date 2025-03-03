# 🏡 Banglore House Price Prediction Machine Learning Project

## **📌 Overview**
This project focuses on predicting **real estate property prices** using machine learning techniques. The goal is to preprocess housing data, train regression models, and evaluate their performance in accurately estimating property prices.  
The workflow includes:
- **Data Cleaning & Preprocessing**
- **Feature Engineering**
- **Categorical Encoding**
- **Model Training** with **Random Forest & XGBoost**
- **Performance Evaluation & Prediction Function Implementation**

---

## **📂 Dataset**
- **Source:** Bengaluru_House_Data.csv from **Kaggle**.
- **Size:** 10,000+ samples with **5 key features**  
- **Key Features:**
  - 📍 **Location**
  - 📏 **Total Square Feet**
  - 🚿 **Number of Bathrooms**
  - 🛏 **Number of Bedrooms (BHK)**
  - 💰 **Price (Target Variable)**  

---

## **🔧 Technologies Used**
- **Python** → Primary programming language  
- **Pandas, NumPy** → Data manipulation & preprocessing  
- **Matplotlib, Seaborn** → Data visualization  
- **Scikit-learn** → Machine learning models & preprocessing  
- **XGBoost, RandomForestRegressor** → Model training & evaluation  

---

## **📂 Dataset Description**
The dataset contains **housing attributes** such as property size, location, and amenities. 
Key preprocessing steps include:
- **Handling missing values**  
- **Encoding categorical variables (One-Hot Encoding)**  
- **Feature scaling & outlier removal using IQR method**  
- **Splitting data into training & testing sets (80/20 split)**  

---

## **📊 Exploratory Data Analysis (EDA)**
EDA was performed using visualization libraries to:
- Understand **price distribution** across different **BHK types**  
- Identify **correlations between property attributes & price**  
- Detect **outliers** using boxplots & scatter plots  
- Analyze **location-based pricing trends**  

---

## **🚀 Model Training & Evaluation**
### **🏆 Models Tested:**
| Model | R² Score |
|----------------------|---------------------|
| **Linear Regression** | `0.7836` |
| **Lasso Regression** | `0.7592` |
| **Decision Tree** | `0.7151` |
| **Random Forest** | **🏆 `0.7966`** |
| **XGBoost** | `0.7944` |

### **📌 Evaluation Metrics**
- **R² Score** → Measures how well the model explains price variance  
- **Mean Absolute Error (MAE)** → Measures prediction accuracy  
- **Feature Importance Analysis** using **Random Forest & XGBoost**  

### **📊 Model Performance**
- **Random Forest achieved the highest accuracy (0.7966 R² Score).**  
- **XGBoost performed similarly (0.7944 R² Score) but required more tuning.**  
- **Linear Regression & Lasso were effective baseline models.**  

---

## **🔍 Key Insights from Analysis**
✅ **High Impact Features**: Total Square Feet, Location, & BHK were the **most significant** predictors.  
✅ **Location Price Trends**: Certain locations showed **significant price variations** due to demand.  
✅ **Non-Linear Relationship**: Price does not increase **linearly** with square footage, requiring complex models like **Random Forest**.  

---

## **📌 Predicting Prices with `predict_price()`**
We implemented a function to predict property prices based on user inputs.


## 🔮 **Future Improvements**
✅ Hyperparameter tuning for model optimization
✅ Deployment of a web-based prediction app using Flask or Streamlit
✅ Feature selection to improve model efficiency
✅ Integration of additional real estate market trends


## 👨‍💻 **Author**
### 👤 Raunaksingh Khalsa
### 📧 raunaksinghkhalsa@gmail.com