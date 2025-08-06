# 💸 Anti-Money Laundering (AML) Detection System

This project aims to detect potentially suspicious transactions that could indicate money laundering using machine learning models. It utilizes advanced ensemble methods like **XGBoost**, **LightGBM**, and **CatBoost** to handle class imbalance and high dimensional transactional data.

## 🔍 Problem Statement

Money laundering involves disguising illegal funds as legitimate income. Detecting such activities is challenging due to:
- Highly imbalanced datasets (very few suspicious transactions)
- Complex transactional patterns
- The evolving nature of financial crime

This project builds an ML pipeline that helps flag high-risk transactions for further investigation.

---

## 🚀 Features

- Preprocessing of anonymized transactional data
- Feature engineering for behavioral insights
- Class imbalance handling using **class weights**
- Training and evaluation of XGBoost, LightGBM, and CatBoost models
- Model evaluation using **ROC-AUC**, **classification reports**, and **confusion matrix**
- Comparison of performance metrics across models

---

## 🛠️ Tech Stack

- **Python** (pandas, numpy, matplotlib, seaborn)
- **Machine Learning**: XGBoost, LightGBM, CatBoost
- **Metrics**: ROC-AUC Score, Precision, Recall, F1-Score
- **Development Tools**: Jupyter Notebook, Git

---

## 📂 Project Structure

