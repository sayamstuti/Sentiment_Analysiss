# Sentiment_Analysiss
# 🐦 Twitter Sentiment Analysis using Machine Learning

A machine learning project that classifies tweets as **Positive** or **Negative** using Natural Language Processing (NLP). This project demonstrates the complete workflow from text preprocessing to model evaluation using the **Sentiment140** dataset.

---

# 📑 Table of Contents

* [Project Overview](#project-overview)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Importing the Dataset](#importing-the-dataset)
* [Data Preprocessing](#data-preprocessing)
* [Text Cleaning & Stemming](#text-cleaning--stemming)
* [Feature Extraction (TF-IDF)](#feature-extraction-tf-idf)
* [Train-Test Split](#train-test-split)
* [Model Training](#model-training)
* [Model Evaluation](#model-evaluation)
* [Prediction on New Tweets](#prediction-on-new-tweets)
* [Results](#results)
* [Contact](#contact)

---

# Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) technique used to determine whether a piece of text expresses a **positive** or **negative** sentiment.

In this project, tweets are preprocessed, transformed into numerical features using TF-IDF, and classified using a Logistic Regression model.

---

# Dataset

**Dataset:** Sentiment140

* Original Dataset Size: **1.6 Million Tweets**
* Sample Used: **50,000 Tweets**
* Classes:

  * **0 → Negative**
  * **1 → Positive**

Dataset Columns:

| Column |
| ------ |
| Target |
| ID     |
| Date   |
| Flag   |
| User   |
| Tweet  |

---

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Regular Expressions (Regex)
* Matplotlib
* Seaborn
* Google Colab

---

# Importing the Dataset

The Sentiment140 dataset was downloaded from Kaggle and loaded into a Pandas DataFrame.

Initial quality checks included:

* Dataset shape
* Missing values
* Target distribution
* Class balance

---

# Data Preprocessing

The preprocessing pipeline included:

* Removing unnecessary columns
* Converting target labels from **4 → 1**
* Handling missing values
* Inspecting class distribution

---

# Text Cleaning & Stemming

Each tweet was cleaned before training the model by:

* Removing URLs and special characters
* Removing punctuation
* Converting text to lowercase
* Removing English stopwords
* Applying Porter Stemming

Example:

```
Loved this movie so much!!

↓

love movi much
```

---

# Feature Extraction (TF-IDF)

Tweets were converted into numerical vectors using **TF-IDF Vectorization**, allowing the machine learning model to understand textual data.

---

# Train-Test Split

The dataset was divided into training and testing sets to evaluate the model on unseen data.

---

# Model Training

A **Logistic Regression** classifier was trained on the processed tweet vectors to predict sentiment.

---

# Model Evaluation

The trained model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Prediction on unseen tweets
* Misclassified tweet analysis

---

# Prediction on New Tweets

The trained model can predict whether a new tweet expresses a **Positive** or **Negative** sentiment after applying the same preprocessing pipeline.

---

# Results

1. Downloaded and prepared the Sentiment140 dataset

2.  Performed text preprocessing using NLP techniques

3. Converted text into TF-IDF feature vectors

4.  Trained a Logistic Regression classifier

5.  Evaluated model performance using multiple metrics

6.  Built a sentiment prediction pipeline for new tweets

---

# Contact

**Name:** Sayam Stuti Shuvadarsini

**Email:** sayamstuti594@gmail.com

**LinkedIn:** www.linkedin.com/in/sayam-stuti-shuvadarsini-8089b43a4
