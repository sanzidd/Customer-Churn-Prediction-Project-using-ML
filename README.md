# 📉 Customer Churn Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=flat&logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

A machine learning project that predicts whether a telecom customer will churn (leave the service) using **Logistic Regression**. The goal is to help businesses proactively identify at-risk customers and take action before losing them.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Dataset](#-dataset)
- [Project Workflow](#-project-workflow)
- [Technologies Used](#-technologies-used)
- [Results](#-results)
- [How to Run](#-how-to-run)
- [Project Structure](#-project-structure)

---

## 🔍 Overview

Customer churn is one of the biggest challenges in the telecom industry. Losing a customer is far more expensive than retaining one. This project builds a binary classification model to predict churn based on customer demographics, account information, and service usage data.

**Target Variable:** `Churn` — whether a customer left the service (Yes/No)

---

## 📂 Dataset

The dataset used is `Customer-Churn-Prediction.csv`, which contains customer-level information including:

- **Demographics** — gender
- **Services subscribed** — Internet Service, Multiple Lines, etc.
- **Account information** — contract type, billing, charges
- **Target** — `Churn` (binary: churned or not)

> ⚠️ The dataset is **imbalanced** — the majority of customers did not churn, which is a real-world challenge addressed during model evaluation.

---

## 🔄 Project Workflow

```
1. Data Loading & Exploration
       ↓
2. Exploratory Data Analysis (EDA)
       ↓
3. Data Preprocessing
   - Dropped irrelevant columns (customerID)
   - Label Encoding for categorical features
   - Standard Scaling for numerical features
       ↓
4. Train-Test Split (75% Train / 25% Test)
       ↓
5. Model Training — Logistic Regression
       ↓
6. Model Evaluation
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)
```

---

## 🛠 Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Preprocessing, model training & evaluation |
| Jupyter Notebook | Development environment |

---

## 📊 Results

The Logistic Regression model was evaluated using the following metrics:

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** — Precision, Recall, F1-Score per class

> The model provides a solid baseline for churn prediction. Given the class imbalance in the dataset, precision and recall are key metrics alongside accuracy.

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/sanzidd/Customer-Churn-Prediction-Project-using-ML.git
   cd Customer-Churn-Prediction-Project-using-ML
   ```

2. **Install required libraries**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. **Open the notebook**
   ```bash
   jupyter notebook "Customer Churn Prediction.ipynb"
   ```

4. **Run all cells** from top to bottom.

---

## 📁 Project Structure

```
Customer-Churn-Prediction-Project-using-ML/
│
├── Customer Churn Prediction.ipynb   # Main notebook with full pipeline
├── Customer-Churn-Prediction.csv     # Dataset
└── README.md                         # Project documentation
```

---

## 🙋‍♂️ Author

**Sanzid**  
[![GitHub](https://img.shields.io/badge/GitHub-sanzidd-black?style=flat&logo=github)](https://github.com/sanzidd)

---

> ⭐ If you found this project helpful, feel free to give it a star!
