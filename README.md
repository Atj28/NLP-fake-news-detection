# Fake News Detection Using Machine Learning

## 📌 Project Overview
This project aims to detect **fake news articles** using Natural Language Processing (NLP) and supervised machine learning models. By training on a labeled dataset of news articles, we build models that classify whether a given news item is *real* or *fake*.

---

## 📂 Dataset
- The dataset consists of news articles with the following fields:
  - **Title**
  - **Text**
  - **Subject**
  - **Label** (`0` for Real, `1` for Fake)
- Preprocessing included:
  - Removing stopwords, punctuation
  - Lemmatization
  - TF-IDF vectorization

---

## 🧠 Models Used
We tested three different classification models:

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Logistic Regression | 90%     | 0.90      | 0.90   | 0.90     |
| Decision Tree       | 82%     | 0.82      | 0.82   | 0.82     |
| Random Forest       | 91%     | 0.91      | 0.91   | 0.91     |

---

## 📊 Visualizations
Several visualizations were created to understand the data and model performance:
- Label distribution
- Word cloud for real vs. fake news
- TF-IDF word importance
- Confusion matrices
- ROC Curves

(*Refer to the `images/` or `visualizations/` directory for plots*)

---

## ✅ Conclusions
- **Random Forest** gave the best overall performance with 91% accuracy.
- **Logistic Regression** also performed well and is computationally lighter.
- **Decision Tree** performed comparatively lower.
- TF-IDF vectorization is effective for fake news detection.

---

## 🚀 Setup & Installation

```bash
