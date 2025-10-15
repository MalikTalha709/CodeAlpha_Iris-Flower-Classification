# 🌸 Iris Flower Classification

This project is part of my **Data Science Internship**.  
It focuses on building and evaluating machine learning models to classify **Iris flower species** based on their physical measurements.

---

## 📘 Project Overview

The **Iris dataset** is a classic and widely used dataset for beginner-level machine learning.  
It contains 150 samples of iris flowers, belonging to three species:

- *Iris Setosa*  
- *Iris Versicolor*  
- *Iris Virginica*

Each sample has four features:

| Feature | Description |
|----------|--------------|
| Sepal length (cm) | Length of the sepal |
| Sepal width (cm) | Width of the sepal |
| Petal length (cm) | Length of the petal |
| Petal width (cm) | Width of the petal |

---

## 🎯 Project Objective

To train a **machine learning model** that can accurately classify the species of an Iris flower based on its sepal and petal dimensions.

---

## 🧩 Workflow Summary

### 1️⃣ Data Loading & Exploration
- Loaded dataset using `scikit-learn` built-in Iris data.
- Checked for missing values, duplicates, and data types.
- Performed statistical summary and visualization:
  - Distribution plots
  - Pairplots
  - Correlation heatmap
  - Boxplots and Violin plots

### 2️⃣ Data Preprocessing
- Verified no missing or duplicate values.
- Applied **feature scaling** using `StandardScaler`.
- Encoded target labels automatically via Scikit-learn.
- Split data into **training (80%)** and **testing (20%)** sets.

### 3️⃣ Model Training
Trained multiple classification algorithms:
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)

### 4️⃣ Model Evaluation
- Used **Accuracy**, **Classification Report**, and **Confusion Matrix** for evaluation.
- Achieved **96.6% accuracy** using **Logistic Regression** (best performing model).

---

## 📊 Results & Insights

| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 0.966 |
| SVM | 0.966 |
| Random Forest | 0.933 |
| KNN | 0.900 |

**Key Insights:**
- Petal features (length & width) are the most important predictors.  
- Setosa is easily separable from other species.  
- Versicolor and Virginica overlap slightly, causing minor misclassification.

---

## 🧠 Conclusion

The Logistic Regression model provided the best trade-off between accuracy and interpretability.  
The dataset is clean, well-balanced, and suitable for supervised learning.  
This project demonstrates understanding of:
- EDA (Exploratory Data Analysis)
- Data Preprocessing
- Model Training & Evaluation
- Classification concepts in Machine Learning

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---
