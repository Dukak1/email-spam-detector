# 📧 Email Spam Classifier

A machine learning project that detects whether an email is **spam** or **not spam (ham)** using Natural Language Processing (NLP) and supervised learning algorithms.

## 📌 Project Overview

This notebook demonstrates a complete ML pipeline for spam email detection.  
It includes data cleaning, text preprocessing, feature extraction using **TF-IDF**, and model training using various classification algorithms.

---

## 📂 Dataset

The dataset contains labeled SMS or email messages marked as `"spam"` or `"ham"` (non-spam).  
Each message is processed using standard NLP techniques.

---

## ⚙️ Technologies Used

- **Python 3**
- **Pandas, NumPy** – Data manipulation
- **NLTK** – Text preprocessing (tokenization, stopword removal, lemmatization)
- **Scikit-learn** – TF-IDF, classifiers, model evaluation
- **XGBoost** – Gradient boosting model
- **Matplotlib, Seaborn** – Visualization

---

## 🧪 Models Implemented

The following models are trained and compared:

- ✅ Multinomial Naive Bayes  
- ✅ Logistic Regression  
- ✅ Random Forest  
- ✅ XGBoost

Each model is evaluated using the following metrics:

| Metric      | Description                          |
|-------------|--------------------------------------|
| Accuracy    | Overall correctness                  |
| Precision   | Correct spam predictions out of all spam-labeled |
| Recall      | Correct spam predictions out of all actual spam |
| F1-Score    | Harmonic mean of precision and recall |

---

## 📊 Model Comparison

A comparison of different classification models based on accuracy, precision, recall, and F1-score:

| Model               | Accuracy | Precision | Recall  | F1-Score |
|--------------------|----------|-----------|---------|----------|
| Naive Bayes        | 0.9776   | 1.0000    | 0.8333  | 0.9091   |
| Logistic Regression| 0.9498   | 0.9608    | 0.6533  | 0.7778   |
| Decision Tree      | 0.9677   | 0.8851    | 0.8733  | 0.8792   |
| Random Forest      | 0.9785   | 1.0000    | 0.8400  | 0.9130   |
| XGBoost            | 0.9749   | 0.9692    | 0.8400  | 0.9000   |

### 🔍 Interpretation

- **Naive Bayes** and **Random Forest** achieved perfect precision, meaning they made no false positive spam predictions.
- **Random Forest** has the **highest F1-score**, showing a strong balance between precision and recall.
- **Logistic Regression** had the lowest recall, indicating it's more conservative in labeling spam.
- **XGBoost** provided a well-rounded performance across all evaluation metrics.


For Kaggle : https://h1.nu/19qGs
