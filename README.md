# 🏥 Insurance Data Analysis using Machine Learning

This project focuses on loading, exploring, and preprocessing an insurance dataset to understand how different customer attributes affect medical insurance charges. The project covers essential data preparation steps required before applying machine learning models.

---

## 📌 Project Overview

The objective of this project is to perform data understanding and preparation on an insurance dataset. The work includes exploratory data analysis and preprocessing techniques to make the data suitable for future machine learning applications.

> ⚠️ Note: Model training and prediction are not included in this project.

---

## 📊 Dataset Description

The dataset contains the following features:

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

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Work Completed

### 1. Data Loading
- Loaded the insurance dataset using Pandas
- Inspected dataset shape, columns, and data types

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of numerical features
- Studied relationships between key variables
- Visualized trends using plots and charts

### 3. Data Preprocessing
- Checked for missing values
- Cleaned and prepared data for analysis

### 4. Encoding Categorical Variables
- Converted categorical features into numerical format
- Ensured compatibility with machine learning algorithms

### 5. Feature Scaling (if required)
- Applied scaling techniques to numerical features
- Normalized data for consistent feature ranges

---

## 📈 Key Insights

- Smoking status has a strong impact on insurance charges
- Age and BMI significantly influence medical costs
- Proper preprocessing improves data readiness for machine learning

---

## ▶️ How to Run the Project

1. Install required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
2. Launch Jupyter Notebook:
```bash
jupyter notebook
```
3.Open insurance.ipynb and run all cells sequentially.
