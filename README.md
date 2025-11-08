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
[![Open In Colab](https://colab.research.google.com/#fileId=https%3A//storage.googleapis.com/kaggle-colab-exported-notebooks/arslaanayub/fake-news-classification-using-random-forest.b22ef951-2d88-423a-8e66-8e551b087a25.ipynb%3FX-Goog-Algorithm%3DGOOG4-RSA-SHA256%26X-Goog-Credential%3Dgcp-kaggle-com%2540kaggle-161607.iam.gserviceaccount.com/20251106/auto/storage/goog4_request%26X-Goog-Date%3D20251106T150401Z%26X-Goog-Expires%3D259200%26X-Goog-SignedHeaders%3Dhost%26X-Goog-Signature%3D917cb71822036cf11bb6a51b7fdbc45fd536285895ef6edf9298f14cabbfa7494ccb5daffa2e98d8078b621bcf87bd1cbb069af1113846d4c5c9694e774edb0370779927d299ffa7de26496826d837c2e6ce4af4b07f6d33f80a61f29de9c5b40340ce68ac116f030f4a9db7d8348bb649c4492f38c896e18fdf74c94d447844197bb32e0c6af5d76823d3b17657a51910931fbfa0ef46ed34b900bc0680a26fceb834787086f4117d5bf297fbc446612c9c9ce4e3bc3526d250de5f1a8ebb5aaf843ab5e6d34b3ed348e1073ab63951180fbfbe23f4c5889d1793ec68f97dd4fa7d874fd0b4b9db7438f9c678a0a42de62fadea622a8f7301684f331323fe3c)

## ⚙️ Installation & Setup

### 1️⃣ Clone this Repository
```bash
git clone https://github.com/<your-username>/fake-news-classification.git
cd fake-news-classification
