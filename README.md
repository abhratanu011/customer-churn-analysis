# Customer Churn Analysis using Machine Learning

## 📌 Overview
This project focuses on **analyzing and predicting customer churn** using machine learning techniques.
The objective is to identify customers who are likely to discontinue a service and understand
the key factors influencing churn.

Two supervised learning models are implemented and compared:
- **Logistic Regression**
- **Gradient Boosting Classifier**

---

## 📊 Dataset
- Customer-level dataset containing demographic, service usage, and account information
- Target variable: **Churn (Yes / No)**
- Dataset is included in the `data/` directory

---

## 🧠 Approach
The project follows these steps:
1. Data loading and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature encoding and scaling
4. Model training using Logistic Regression
5. Model training using Gradient Boosting
6. Model evaluation and comparison

---

## ⚙️ Models Used
### Logistic Regression
- Baseline classification model
- Interpretable and efficient for binary classification

### Gradient Boosting Classifier
- Ensemble-based model
- Captures non-linear relationships
- Improves predictive performance over baseline

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📈 Results

The performance of the machine learning models is summarized below:

| Model | Accuracy | Precision | Recall | F1 Score |
|------|----------|-----------|--------|----------|
| Logistic Regression | 0.820 | 0.683 | 0.595 | 0.636 |
| Gradient Boosting | 0.809 | 0.672 | 0.544 | 0.601 |

### Key Insights
- Logistic Regression achieved the best overall performance across all evaluation metrics
- Gradient Boosting did not outperform the baseline model, indicating limited non-linear patterns
- Recall values suggest scope for improvement through class imbalance handling or threshold tuning
