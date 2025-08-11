<h1 align="center">💳 Credit Card Fraud Detection using Machine Learning</h1>

<p align="center">
  🔍 A machine learning project to detect fraudulent transactions in real-world credit card data using classification algorithms.
</p>

---

## 📌 Table of Contents

- [📌 Table of Contents](#-table-of-contents)
- [📖 Overview](#-overview)
- [📁 Dataset](#-dataset)
- [🧰 Requirements](#-requirements)
- [🚀 How to Run](#-how-to-run)
- [🧠 Methodology](#-methodology)
- [📊 Results](#-results)
- [📷 Visuals](#-visuals)
- [🧑‍💻 Author](#-author)
- [📄 License](#-license)

---

## 📖 Overview

This project uses supervised machine learning to predict whether a credit card transaction is fraudulent or legitimate. It uses a Kaggle dataset that contains anonymized transaction data with class imbalance (fraud cases are rare).

### ✅ Models Implemented:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📁 Dataset

The dataset used is:
- 📦 `creditcard.csv` — Included in this repo

Source:  
[Kaggle: Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- 284,807 transactions
- 492 fraudulent
- Features `V1–V28` are anonymized via PCA
- Highly imbalanced dataset

---

## 🧰 Requirements

Install all dependencies:

```bash
pip install -r requirements.txt

## Libraries used:
pandas
numpy
sklearn
matplotlib
seaborn
In this project we try to detect credit card fraud using Logistic Regression,Random Forest, Decision Tree also we preprocessing the data.

### You can also install them manually:
pip install pandas numpy matplotlib seaborn scikit-learn

##🚀 How to Run
📥 Clone the repository:
git clone https://github.com/kumar-shubham1/credit-card-fraud-detection.git
cd credit-card-fraud-detection

📦 Install dependencies:
pip install -r requirements.txt

📊 Launch Jupyter Notebook:
jupyter notebook credit-card-fraud-detection.ipynb
▶️ Run the cells step-by-step to see the analysis and results.


##🧠 Methodology
📌 Key Steps:
Loaded and explored the dataset
Visualized class imbalance
Applied standard scaling to the Amount feature
Used train-test split (80-20)
Trained and evaluated 3 ML classifiers
Compared accuracy, precision, recall, and F1-score

📷 Also includes:

Confusion Matrix
Classification Report
ROC Curve (optional)


##📊 Results
Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	~99.2%	Good	Moderate	Moderate
Decision Tree	~99.8%	Better	High	High
Random Forest	~99.9%	Excellent	High	Excellent ✅

➡️ Random Forest performed the best overall.


##📷 Visuals
Visualization	Description
Methodology	Step-by-step methodology flow
Confusion Matrix	Shows fraud vs legit classification accuracy
Feature Importance	Displays top contributors to fraud detection


##🧑‍💻 Author : Shubham Kumar
👨‍🎓 B.Tech CSE Student
##📧 shubhamvermaa045@gmail.com
## 🌐 GitHub :- https://github.com/kumar-shubham1

##📄 License
This project is open for educational purposes.
Dataset is licensed and provided by Kaggle.

---

##✅ Just copy and paste this into your `README.md` file and save it.  
Then run:

```bash
git add README.md
git commit -m "Updated full README with project details"
git push



