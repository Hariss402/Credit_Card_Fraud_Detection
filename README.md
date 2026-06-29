# 💳 Credit Card Fraud Detection

A machine learning project for detecting fraudulent credit card transactions using multiple classification algorithms and techniques for handling highly imbalanced datasets.

---

## 📌 Project Overview

Credit card fraud detection is a challenging binary classification problem because fraudulent transactions account for only **492 out of 284,807 transactions (0.172%)**. This project explores several machine learning models and sampling techniques to accurately identify fraudulent transactions while minimizing false positives and false negatives.

The project compares classical machine learning algorithms and a neural network using evaluation metrics better suited for imbalanced datasets than accuracy alone.

---

## 📊 Dataset

- **Source:** Kaggle Credit Card Fraud Detection Dataset
- **Total Transactions:** 284,807
- **Fraudulent Transactions:** 492
- **Features:** 30 numerical features (28 anonymized PCA-transformed features, Time, Amount)
- **Target Variable:** Class
  - **0:** Legitimate Transaction
  - **1:** Fraudulent Transaction

---

## 🚀 Project Workflow

- Data Exploration & Cleaning
- Exploratory Data Analysis (EDA)
- Feature Scaling
- Handling Class Imbalance
  - Random Under-Sampling
  - SMOTE Over-Sampling
- Correlation Analysis
- Outlier Detection & Removal
- Dimensionality Reduction using t-SNE
- Model Training
- Model Evaluation
- Neural Network Implementation

---

## 🤖 Models Implemented

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Neural Network (TensorFlow/Keras)

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Precision-Recall Curve

Since this is a highly imbalanced classification problem, greater emphasis is placed on precision, recall, F1-score, and ROC-AUC rather than overall accuracy.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- TensorFlow / Keras

---

## 📁 Repository Structure

```
Credit_Card_Fraud_Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── data
    ├── readme.md
├── requirements.txt
├── requirements_dev.txt
├── .gitignore
└── README.md
```

---

## 🎯 Key Learnings

- Working with highly imbalanced datasets
- Data preprocessing and feature engineering
- Random Under-Sampling and SMOTE
- Comparing multiple machine learning algorithms
- Building neural networks using TensorFlow/Keras
- Evaluating classification models using fraud-specific metrics

---

## 🚀 Future Improvements

- Hyperparameter optimization
- Ensemble learning methods (XGBoost, LightGBM)
- Explainable AI using SHAP
- Real-time fraud detection pipeline
- Web deployment using Streamlit

---

## 📜 License

This project is intended for educational and portfolio purposes.