# 💳 Credit Card Fraud Detection

This project uses supervised machine learning to classify credit card transactions as fraudulent or legitimate. It leverages a highly imbalanced dataset from Kaggle and implements multiple models to compare performance.

## 📁 Dataset

- Source: Kaggle  
- File: `creditcard.csv`  
- 284,807 transactions  
- 492 fraud cases  
- Features V1–V28 are anonymized via PCA  
- Target: `Class` (1 = Fraud, 0 = Legitimate)

## ✅ Models Implemented

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

## 🧠 Methodology

- Data loading and exploration  
- Visualizing class imbalance  
- Scaling the `Amount` feature  
- Train-test split (80/20)  
- Model training and evaluation  
- Metrics compared: Accuracy, Precision, Recall, F1-score  
- Visualizations: Confusion Matrix, ROC Curve, Feature Importance

## 📊 Results

| Model               | Accuracy | Precision | Recall  | F1-Score |
|--------------------|----------|-----------|---------|----------|
| Logistic Regression| ~99.2%   | Good      | Moderate| Moderate |
| Decision Tree      | ~99.8%   | Better    | High    | High     |
| Random Forest ✅    | ~99.9%   | Excellent | High    | Excellent|

➡️ Random Forest performed the best overall.

## 🧰 Requirements

Install dependencies:

```bash
pip install -r requirements.txt

Or manually
pip install pandas numpy matplotlib seaborn scikit-learn

git clone https://github.com/Amanhaldiya/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
jupyter notebook credit-card-fraud-detection.ipynb


