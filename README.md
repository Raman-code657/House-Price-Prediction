# House-Price-Prediction
#  Linear Regression – Housing Price Prediction

This project implements **simple and multiple linear regression** models using the **Housing Price Prediction Dataset**. The goal is to understand regression modeling, evaluation metrics, and model interpretation.

---

## 📂 Dataset

Dataset used: [Housing Price Prediction - Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

---

## 📌 Objectives

- Implement **simple & multiple linear regression**
- Understand **model training**, **evaluation**, and **interpretation**
- Use metrics like **MSE**, **MAE**, and **R²**
- Visualize results with **matplotlib** and **seaborn**

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🔁 Workflow

### 1. Import and Preprocess the Data
- Load the dataset
- Handle missing values
- Encode categorical features

### 2. Split the Dataset
```python
X_train, X_test, y_train, y_test = train_test_split(...)
