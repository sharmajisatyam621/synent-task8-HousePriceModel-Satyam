# 🏠 Housing Data Analysis using KNN Imputation

## 📌 Project Overview

This project focuses on analyzing a housing dataset and handling missing values using the **K-Nearest Neighbors (KNN) Imputer**.
The goal is to clean the dataset, explore relationships between features, and prepare it for further machine learning tasks.

---

## 🎯 Objectives

* Perform **data cleaning and preprocessing**
* Handle **missing values using KNN Imputer**
* Convert **categorical data into numerical format**
* Visualize **feature relationships**
* Prepare dataset for **model building**

---

## 📂 Dataset Description

The dataset contains housing-related information such as:

* **Median Income**
* **House Value**
* **Total Rooms / Bedrooms**
* **Population**
* **Households**
* **Ocean Proximity (Categorical Feature)**

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas (Data Handling)
* NumPy (Numerical Operations)
* Matplotlib & Seaborn (Visualization)
* Scikit-learn (KNN Imputer)

---

## 🔍 Data Preprocessing Steps

### 1. Data Loading

* Dataset loaded using Pandas
* Initial inspection using `.head()`, `.info()`, `.describe()`

### 2. Missing Value Handling

* Identified missing values using `.isnull().sum()`
* Applied **KNN Imputer** to fill missing numeric values

### 3. Categorical Encoding

* Converted categorical variables using **One-Hot Encoding**

---

## 📊 Exploratory Data Analysis

### 📈 Visualizations Used

* Distribution Plot (House Prices)
* Scatter Plot (Income vs House Value)
* Correlation Heatmap

---

## 🧠 Key Insights

* 📊 **Median Income strongly affects house prices**
* 🏠 Higher number of rooms often leads to higher house value
* 🔗 Strong correlations exist between housing features
* ⚠️ Missing values can significantly impact model performance

---

## 🚀 How to Run the Project

1. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Open the notebook:

```bash
Housing.ipynb
```

3. Run all cells step-by-step

---

## 📷 Output

The notebook generates:

* Cleaned dataset
* Visualizations (graphs & heatmap)
* Imputed dataset using KNN

---

## 🧠 Business / Practical Use

* Helps in **real estate price prediction**
* Useful for **data preprocessing in ML pipelines**
* Improves **data quality for accurate predictions**

---

## 📌 Future Enhancements

* Apply Machine Learning models (Regression)
* Feature selection & scaling
* Model evaluation and tuning

---

## 👤 Author

**Satyam Sharma**

---
