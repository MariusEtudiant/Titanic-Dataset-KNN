# 🚢 Titanic Dataset Analysis

## 📖 Overview

The Titanic dataset is one of the most iconic datasets in machine learning and data science. It offers an opportunity to explore **data preprocessing**, **feature engineering**, and **classification models** by predicting the survival of passengers based on various features such as age, gender, class, and more.

### 🔗 [Dataset Presentation and Resources](https://gitlab.inria.fr/chxu/python-pour-ia-2024/-/tree/main/Python_pandas_numpy?ref_type=heads)
This repository provides the dataset, essential resources, and guidance for working with **Python**, **Pandas**, and **NumPy** to analyze and build machine learning models.

---

## 🎯 Objective

The main goal is to predict whether a passenger survived the Titanic disaster using machine learning techniques. This involves:
- Preprocessing the data to handle missing values.
- Performing exploratory data analysis (EDA).
- Building and evaluating classification models.

---

## 🚀 Approach

### 1️⃣ Data Preprocessing
- **Handling Missing Values**:
  - Imputed missing ages using median values grouped by passenger class and gender.
  - Filled missing values in categorical features (e.g., Embarked) with the most frequent category.
- **Feature Encoding**:
  - Converted categorical variables (e.g., Gender, Embarked) into numerical representations using one-hot encoding.

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed survival rates across different features like **Pclass**, **Sex**, and **Embarked**.
- Visualized correlations using **Seaborn** and **Matplotlib**.

### 3️⃣ Machine Learning Models

#### **K-Nearest Neighbors (KNN)**
- Chose KNN for its simplicity and ability to classify passengers based on their proximity in feature space.

## 📊 Results

| Model                | Accuracy | Precision | Recall |
|----------------------|----------|-----------|--------|
| KNN                  | 0.84     | 0.82      | 0.81   |

---

## 🛠️ Tools and Libraries

- **Python**
- **Pandas** & **NumPy**: Data manipulation and analysis.
- **Matplotlib** & **Seaborn**: Visualizations and insights.

---

## ✨ Reflections

Working on the Titanic dataset provided valuable insights into:
- The importance of preprocessing and EDA in machine learning.

---

Feel free to explore the dataset and my implementation in detail. If you have any questions or suggestions, don’t hesitate to reach out! 😊
