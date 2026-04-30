# 🤖 Machine Learning Mini Projects

This repository contains two beginner-friendly machine learning projects:

1. 🏠 House Price Prediction (Linear Regression)
2. 🛍️ Customer Segmentation (K-Means Clustering)

---

## 📌 Project 1: House Price Prediction

### 🔍 Overview

Predicts house prices using a Linear Regression model based on selected features.

### 📊 Features Used

* GrLivArea → Living area (sq ft)
* BedroomAbvGr → Number of bedrooms
* FullBath → Number of bathrooms

### 🎯 Target

* SalePrice

### ⚙️ Workflow

* Data cleaning
* Feature selection
* Handling missing values
* Train-test split
* Model training
* Evaluation using RMSE
* Visualization (Actual vs Predicted)

### 📁 Output

* `submission.csv` with predicted house prices

---

## 📌 Project 2: Customer Segmentation

### 🔍 Overview

Uses K-Means Clustering to group mall customers into different segments based on spending behavior.

### 📊 Features Used

* Annual Income (k$)
* Spending Score (1–100)

### ⚙️ Workflow

* Data loading
* Feature selection
* Elbow method to find optimal clusters
* Model training (K=5)
* Cluster visualization
* Assign cluster labels

---

## 📈 Visualizations

* Elbow Method Graph
* Customer Cluster Plot
* Actual vs Predicted Prices Graph

---

## 🚀 How to Run

### 1. Install dependencies

```bash
pip install pandas matplotlib scikit-learn
```

### 2. Run scripts

```bash
python task1_linear_regression.py
python task2_kmeans.py
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## 📂 Repository Structure

```
├── train.csv
├── test.csv
├── Mall_Customers.csv
├── task1_linear_regression.py
├── task2_kmeans.py
├── submission.csv
└── README.md
```

---

## 📌 Future Improvements

* Use advanced ML models (Random Forest, XGBoost)
* Feature engineering
* Hyperparameter tuning
* Deploy as a web app

---

## 👨‍💻 Author

Your Name

---

## ⭐ Support

If you like this project, consider giving it a star ⭐
