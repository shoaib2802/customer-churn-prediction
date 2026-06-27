# 🔍 Customer Churn Prediction

Predicting telecom customer churn using machine learning classification algorithms.

## 📌 Problem Statement
Telecom companies lose revenue when customers churn. This project builds a model to identify at-risk customers so the business can take proactive retention action.

## 📊 Dataset
- IBM Telco Customer Churn dataset (Kaggle)
- 7,043 rows | 21 features
- Target: `Churn` (Yes/No)

## 🛠️ Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, XGBoost, imbalanced-learn (SMOTE), Matplotlib, Seaborn

## ⚙️ Approach
1. Data cleaning & preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature encoding & scaling
4. SMOTE to handle class imbalance
5. Model training: Logistic Regression, Random Forest, XGBoost
6. Evaluation: Accuracy, ROC-AUC, Confusion Matrix

## 📈 Results
| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | 75.37% | 0.86 |
| Random Forest | 79.28% | 0.84 |
| XGBoost | 78.92% | 0.83 |

**Best Model: Random Forest** ✅

## 💡 Key Findings
- Month-to-month contract customers churn at 3x the rate of annual contract customers
- Customers with tenure < 12 months are highest risk
- High monthly charges strongly correlate with churn

## ▶️ How to Run
pip install -r requirements.txt

jupyter notebook churn_prediction.ipynb

Note: Download the dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and place the CSV in the same folder.
