# Email Spam Classification – Machine Learning Project

Welcome to the **Email Spam Classification** project!  
This project focuses on building a **machine learning model** to automatically classify emails as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques.

---

## 🔹 Project Overview

Email spam is a major challenge in digital communication.  
In this project, I implemented an **end-to-end spam detection system** that analyzes email text and predicts whether an email is spam or legitimate.

The project covers the complete ML workflow:
- Text preprocessing
- Feature extraction
- Model training
- Evaluation
- Prediction on new emails

---

## 🔹 Objective

- Automatically classify emails as **Spam** or **Ham**
- Reduce unwanted and malicious email content
- Apply **NLP + Machine Learning** techniques on real-world text data

---

## 🔹 Dataset

- Public email spam dataset (e.g., SMS Spam Collection / Email Spam Dataset)
- Classes:
  - `Spam`
  - `Ham` (Not Spam)

---

## 🔹 Approach

### 🔸 Text Preprocessing
- Lowercasing text
- Removing punctuation and special characters
- Stopword removal
- Tokenization
- Stemming / Lemmatization

### 🔸 Feature Extraction
- Bag of Words (BoW)
- TF-IDF (Term Frequency – Inverse Document Frequency)

### 🔸 Machine Learning Models
- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)

---

## 🔹 Key Features

- NLP-based text cleaning and processing
- Vectorization using TF-IDF
- Binary classification (Spam vs Not Spam)
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Predictions on unseen email text

---

## 🔹 Tech Stack

- **Programming Language:** Python 3.x
- **Libraries & Frameworks:**
  - `numpy`, `pandas`
  - `scikit-learn`
  - `nltk`
  - `matplotlib`, `seaborn`
- **Tools:** Jupyter Notebook

---

## 🔹 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/email-spam-classification.git
   cd email-spam-classification

Input Email:
"Congratulations! You have won a free lottery ticket."

Prediction:
Spam
