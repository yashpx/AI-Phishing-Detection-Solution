# 🛡️ AI-Powered Phishing Detection System

> 🔍 A machine learning solution to classify emails and URLs as "phishing" or "legitimate" using Logistic Regression.  
> 🧠 Built for the subject **AI for Cybersecurity (CSIT375)** using Kaggle's phishing dataset.

![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)
![License](https://img.shields.io/badge/status-Completed-brightgreen)
![Logistic Regression](https://img.shields.io/badge/model-Logistic%20Regression-yellow)

---

## 📖 Overview

Phishing attacks are one of the most prevalent cyber threats globally. This project presents an AI-powered phishing detection system designed to detect phishing websites or emails using machine learning.

We used a dataset sourced from Kaggle containing labeled phishing and legitimate entries. A Logistic Regression model was trained after preprocessing and scaling the data, achieving **94% accuracy** on the test set.

---

## ✨ Features

- Binary classification of phishing vs legitimate data
- End-to-end ML pipeline from preprocessing to model evaluation
- Evaluation using Accuracy, Precision, Recall, F1-score
- Achieves **94%+** performance across all metrics
- Clean and scalable codebase

---

## 🗂 Project Structure

📦 ai-phishing-detection
├── 375_code.py # Main Python script with full implementation
├── dataset_phishing.csv # Dataset used from Kaggle
├── README.md # Project documentation


---

## 📊 Results Summary

| Metric    | Value |
|-----------|-------|
| Accuracy  | 94%   |
| Precision | 94%   |
| Recall    | 95%   |
| F1-Score  | 94%   |

> 📌 Logistic Regression proved to be highly effective for this classification task, balancing both precision and recall.

---

## ⚙️ Installation & Usage

# ✅ Requirements

'''bash
pip install pandas scikit-learn
▶️ Run the Script
bash
Copy
Edit
python 375_code.py
Make sure dataset_phishing.csv is in the same directory.

# 🔧 Preprocessing Steps
Label Encoding
Converts target column status (phishing or legitimate) to numeric.

Removing Non-Numeric Columns
Columns with object type are dropped to ensure numeric consistency.

Train-Test Split
80-20 stratified split for balanced model evaluation.

Feature Scaling
Applied StandardScaler to ensure model convergence and fair weight distribution.

# 🤖 Model Details
Algorithm: Logistic Regression

Training Data: 80% of total (9144 samples)

Test Data: 20% of total (2286 samples)

Optimization: Gradient Descent with max_iter=1000

Target Variable: status (encoded: 1 = phishing, 0 = legitimate)

# 📌 Dataset
Source: Kaggle - Web Page Phishing Detection Dataset
Features: 87 numeric attributes after preprocessing

# 📜 License & Use
This project is submitted as part of CSIT375 – AI for Cybersecurity at the University of Wollongong in Dubai.
For educational purposes only. Not intended for production use.
