# 📊 Customer Churn Prediction using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</p>

---

## 📖 Project Overview

Customer churn refers to customers who stop using a company's products or services. Predicting customer churn is an important business problem because retaining existing customers is often more cost-effective than acquiring new ones.

This project uses **Machine Learning** and **Logistic Regression** to predict whether a customer is likely to leave the company based on customer demographics, account information, and subscribed services.

---

## 🎯 Project Objectives

- Predict whether a customer will churn or stay.
- Perform data cleaning and preprocessing.
- Analyze customer behavior and service usage.
- Build a classification model using Logistic Regression.
- Evaluate model performance using classification metrics.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| 🐍 Python | Programming Language |
| 🐼 Pandas | Data Cleaning & Analysis |
| 🔢 NumPy | Numerical Computations |
| 📊 Matplotlib | Data Visualization |
| 🌊 Seaborn | Statistical Visualization |
| 🤖 Scikit-Learn | Machine Learning |
| 💻 Jupyter Notebook | Development Environment |

---

## 📂 Dataset Information

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains information about:

- Customer demographics
- Services subscribed by customers
- Account information
- Billing details
- Customer churn status

### Target Variable

```text
Churn
0 → Customer Stays
1 → Customer Leaves
```

---

## 📊 Dataset Summary

| Feature | Value |
|----------|--------|
| Total Records | 7032 |
| Total Features | 30 |
| Algorithm Used | Logistic Regression |
| Problem Type | Classification |
| Model Accuracy | 78.75% |

---

## 🔄 Project Workflow

```text
Data Collection
       ↓
Data Cleaning
       ↓
Handling Missing Values
       ↓
Feature Encoding
       ↓
Train-Test Split
       ↓
Model Training
       ↓
Prediction
       ↓
Performance Evaluation
```

---

## 📈 Model Performance

### Accuracy Score

```text
Accuracy: 78.75%
```

### Confusion Matrix

```text
[[915 118]
 [181 193]]
```

### Classification Report

| Metric | Class 0 (Stay) | Class 1 (Leave) |
|--------|---------------|----------------|
| Precision | 0.83 | 0.62 |
| Recall | 0.89 | 0.52 |
| F1 Score | 0.86 | 0.56 |

---

## 🔍 Key Insights

📌 Customers with **Fiber Optic Internet Service** were more likely to churn.

📌 Customers using **Electronic Check** payment methods showed higher churn rates.

📌 **Senior Citizens** had a relatively higher probability of leaving.

📌 Contract type and service subscriptions significantly influenced customer retention.

📌 Customer churn prediction can help businesses improve customer satisfaction and reduce revenue loss.

---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/Kavyaa13/customer-churn-prediction.git
cd customer-churn-prediction
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
customer_churn_prediction.ipynb
```

---

## 💡 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Handling Missing Values
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Classification Algorithms
- Model Evaluation
- Feature Importance Analysis
- End-to-End Machine Learning Workflow

---

## 🔮 Future Improvements

- Implement Random Forest and XGBoost models.
- Perform Hyperparameter Tuning.
- Deploy the model using Streamlit.
- Handle class imbalance techniques.
- Compare multiple classification algorithms.

---

## 👩‍💻 Author

**Kavya**

Artificial Intelligence and Machine Learning Student  
Passionate about Data Science, Machine Learning, and Building Real-World AI Projects.

🔗 GitHub: https://github.com/Kavyaa13

---

### ⭐ If you found this project useful, consider giving it a star!
