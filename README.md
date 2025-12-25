# 🧠🏥 Machine Learning Practice Projects

This repository contains two machine learning practice projects focused on **data understanding, exploratory data analysis (EDA), and preprocessing** using real-world healthcare datasets. These projects build a strong foundation for applying machine learning models in the future.

---

## 📌 Projects Overview

The goal of these projects is to gain hands-on experience with real datasets and learn how to prepare data effectively before model building. The work includes data loading, visualization, preprocessing, encoding categorical variables, and feature scaling.

> ⚠️ Note: Model training and prediction are not included in these projects.

---

# 🏥 Project 1: Insurance Data Analysis using Machine Learning

This project focuses on analyzing an insurance dataset to understand how different customer attributes affect medical insurance charges.

---

## 📊 Dataset Description (Insurance)

| Feature   | Description |
|----------|------------|
| age      | Age of the insured person |
| sex      | Gender (male/female) |
| bmi      | Body Mass Index |
| children | Number of children covered |
| smoker   | Smoking status |
| region   | Residential region |
| charges  | Medical insurance cost |

---

## 🔍 Work Completed (Insurance)

### 1. Data Loading
- Loaded the insurance dataset using Pandas
- Inspected dataset shape, columns, and data types

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of numerical features
- Studied relationships between age, BMI, smoking status, and charges
- Visualized trends using plots and charts

### 3. Data Preprocessing
- Checked for missing values
- Cleaned and formatted the dataset

### 4. Encoding Categorical Variables
- Converted categorical features into numerical format
- Ensured compatibility with machine learning algorithms

### 5. Feature Scaling (if required)
- Applied scaling techniques to numerical features
- Normalized data for consistent feature ranges

---

## 📈 Key Insights (Insurance)

- Smoking status has a strong impact on insurance charges
- Age and BMI significantly influence medical costs
- Proper preprocessing improves data readiness for ML workflows

---

# ❤️ Project 2: Heart Disease Data Analysis using Machine Learning

This project focuses on analyzing a heart disease dataset to understand how medical and lifestyle attributes relate to heart disease risk.

---

## 📊 Dataset Description (Heart Disease)

The dataset includes medical attributes such as:
- Age
- Gender
- Chest pain type
- Resting blood pressure
- Cholesterol levels
- Fasting blood sugar
- ECG results
- Maximum heart rate
- Exercise-induced angina
- Other clinical indicators

---

## 🔍 Work Completed (Heart Disease)

### 1. Data Loading
- Loaded the heart disease dataset
- Examined data types, structure, and summary statistics

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of medical features
- Studied relationships between health indicators and heart disease
- Used visualizations to identify patterns and correlations

### 3. Data Preprocessing
- Checked for missing and inconsistent values
- Cleaned the dataset for analysis

### 4. Encoding Categorical Variables
- Converted categorical medical features into numerical values
- Prepared data for machine learning compatibility

### 5. Feature Scaling (if required)
- Applied scaling to numerical features where necessary
- Ensured balanced feature ranges

---

## 📈 Key Insights (Heart Disease)

- Certain medical attributes strongly correlate with heart disease risk
- EDA helps in identifying critical health indicators
- Clean and well-preprocessed data is essential for reliable ML models

---

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## ▶️ How to Run the Projects

1. Install required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
2. Launch Jupyter Notebook:
```bash
jupyter notebook
```
3. Open the notebooks and run all cells sequentially:

insurance.ipynb
Heart_disease.ipynb

## 📚 Learning Outcomes

- Understanding real-world dataset structures  
- Hands-on experience with Exploratory Data Analysis (EDA)  
- Practical knowledge of data preprocessing techniques  
- Experience encoding categorical data and feature scaling  
- Strong foundation for future machine learning projects  
