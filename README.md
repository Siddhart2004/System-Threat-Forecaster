# 🛡️ System Threat Forecaster

A machine learning-based project designed to forecast potential system threats using various classification models and preprocessing pipelines.

---

## 📌 Overview

Cybersecurity is a growing concern, and being able to predict system threats can help in proactive risk management. This project explores the application of supervised learning techniques to classify threats in a given system using structured data. It includes exploratory data analysis (EDA), feature engineering, model training, and evaluation using real-world-like datasets.

---

## 🚀 Features

- Data Preprocessing: Missing value handling, encoding, scaling
- Dimensionality Reduction: PCA (Principal Component Analysis)
- Classification Models: 
  - Random Forest Classifier
  - Logistic Regression
  - XGBoost Classifier
- Hyperparameter Tuning: GridSearchCV, RandomizedSearchCV
- Model Evaluation: Accuracy, Confusion Matrix, Classification Report

---

## 📂 Dataset

[Dataset link](https://drive.google.com/drive/folders/1ks6mVzhXVwOIqRjNjA3vkrt2GwNe2qLN?usp=sharing)

The datasets used (`train.csv` and `test.csv`) .

- `train.csv`: Used for model training and validation.
- `test.csv`: Used for model inference.

---

## 📊 Sample Output

You can expect evaluation metrics like:

- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)
  
---

## 🧰 Requirements

Install the required libraries before running the notebook:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost

## 📈 How to Use
Clone this repository:

git clone https://github.com/your-username/system-threat-forecaster.git
cd system-threat-forecaster

Open the notebook:

jupyter notebook system-threat-forecaster.ipynb
