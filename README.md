# 📰 Fake News Classification using Random Forest

A comprehensive machine learning project that detects **fake news** using Natural Language Processing (NLP) and a **Random Forest classifier**.  
This notebook demonstrates the complete workflow — from text cleaning and feature extraction to model training and evaluation — using the **WELFake dataset**.

---

## 🚀 Project Overview

The internet is filled with misinformation that spreads rapidly through social platforms.  
This project focuses on building a reliable text classification model to identify and label news articles as either **Fake** or **Real**.  

By leveraging **TF-IDF features** and an ensemble-based **Random Forest model**, the notebook achieves high classification accuracy and robustness against noisy data.

---

## 🧠 Features

- Text cleaning using regex, stopword removal, and lemmatization (NLTK)
- TF-IDF feature extraction for converting text into numeric form
- Random Forest classifier for high-performance binary classification
- Evaluation with confusion matrix and performance metrics
- Visualization of model results using Matplotlib and Seaborn

---

## 📂 Dataset

- **Dataset Name:** [WELFake Dataset](https://www.kaggle.com/datasets)
- **Source:** `/kaggle/input/fake-news-classification/WELFake_Dataset.csv`
- **Description:**  
  Contains labeled news articles with columns such as `title`, `text`, and `label` (`Fake` or `Real`).

---

## 🧩 Workflow

| Step | Description |
|------|--------------|
| **Data Loading** | Load the WELFake dataset using `pandas` |
| **Preprocessing** | Clean text, remove stopwords, lemmatize using WordNet |
| **Feature Extraction** | Convert text to TF-IDF vectors |
| **Model Training** | Train Random Forest classifier using scikit-learn |
| **Evaluation** | Generate confusion matrix, accuracy, precision, recall, F1-score |
| **Visualization** | Plot confusion matrix with Seaborn heatmap |

---
## 🚀 Run it in Google Colab
Click to open in Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]

## ⚙️ Installation & Setup

### 1️⃣ Clone this Repository
```bash
git clone https://github.com/<your-username>/fake-news-classification.git
cd fake-news-classification
