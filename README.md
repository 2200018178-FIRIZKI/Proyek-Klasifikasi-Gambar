# 🎮 Sentiment Analysis of Free Fire Reviews Using Machine Learning & Deep Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success)
![Deep Learning](https://img.shields.io/badge/Deep-Learning-red)
![NLP](https://img.shields.io/badge/NLP-TF--IDF%20%7C%20Word2Vec-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📖 Project Overview

This project aims to perform **Sentiment Analysis** on user reviews of the **Garena Free Fire** mobile game collected from the **Google Play Store**.

The project covers the complete Natural Language Processing (NLP) pipeline, starting from review scraping, text preprocessing, sentiment labeling, feature extraction, machine learning model training, deep learning implementation, and model evaluation.

The main objective is to identify whether user reviews express **positive**, **neutral**, or **negative** sentiment and compare several classification approaches.

---

# 🎯 Objectives

* Scrape Free Fire user reviews from Google Play Store.
* Build a clean sentiment analysis dataset.
* Perform Indonesian text preprocessing.
* Compare traditional Machine Learning and Deep Learning models.
* Evaluate classification performance using standard metrics.

---

# 📊 Dataset Information

### Source

Google Play Store

Application:
**Garena Free Fire**

### Dataset Summary

| Information       |          Value |
| ----------------- | -------------: |
| Total Reviews     |     **12,000** |
| Total Features    | **12 Columns** |
| Sentiment Classes |              3 |
| Language          |     Indonesian |

---

## Dataset Features

| Column               | Description         |
| -------------------- | ------------------- |
| reviewId             | Review ID           |
| userName             | Username            |
| userImage            | User profile image  |
| content              | Review text         |
| score                | Rating (1-5)        |
| thumbsUpCount        | Helpful votes       |
| reviewCreatedVersion | App version         |
| at                   | Review date         |
| replyContent         | Developer reply     |
| repliedAt            | Reply date          |
| appVersion           | Application version |
| sentiment            | Sentiment label     |

---

# 😊 Sentiment Distribution

The final labeled dataset consists of:

| Sentiment |      Total | Percentage |
| --------- | ---------: | ---------: |
| Positive  | **10,288** | **85.73%** |
| Negative  |  **1,415** | **11.79%** |
| Neutral   |    **297** |  **2.48%** |

This distribution indicates that most Free Fire players provide **positive feedback**, while a smaller proportion express dissatisfaction or neutral opinions.

---

# 📂 Project Structure

```text
.
├── Free_Fire_Scraping.ipynb
├── Sentiment_Analysis_Training.ipynb
├── free_fire_reviews_with_sentiment.csv
├── requirements.txt
└── README.md
```

---

# ⚙️ Technologies Used

## Programming Language

* Python

## Libraries

### Data Processing

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### NLP

* NLTK
* Sastrawi
* Regex

### Feature Extraction

* TF-IDF
* Word2Vec

### Machine Learning

* Support Vector Machine (SVM)
* Random Forest

### Deep Learning

* TensorFlow
* Keras
* LSTM

---

# 🔄 Project Workflow

```text
Google Play Store
        │
        ▼
Review Scraping
        │
        ▼
Dataset Collection
        │
        ▼
Data Cleaning
        │
        ▼
Text Preprocessing
        │
        ▼
Feature Extraction
(TF-IDF / Word2Vec)
        │
        ▼
Machine Learning Models
        │
        ▼
Deep Learning Model
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
```

---

# 🧹 Data Preprocessing

The preprocessing pipeline includes:

* Lowercase conversion
* Removing URLs
* Removing punctuation
* Removing numbers
* Removing special characters
* Removing emojis
* Removing extra whitespace
* Tokenization
* Stopword Removal
* Indonesian Stemming using Sastrawi

---

# 🔤 Feature Extraction

Two feature extraction techniques are implemented.

## TF-IDF

Converts text into numerical vectors using term frequency and inverse document frequency.

## Word2Vec

Learns semantic vector representations of words before converting them into document vectors.

---

# 🤖 Machine Learning Models

The project compares several models:

* Support Vector Machine (SVM)
* Random Forest
* Long Short-Term Memory (LSTM)

Each model is trained using the processed review dataset and evaluated using classification metrics.

---

# 📈 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

# 📌 Project Results

The project successfully:

* Collected **12,000** Free Fire reviews.
* Built a labeled sentiment dataset with **3 sentiment classes**.
* Applied Indonesian NLP preprocessing techniques.
* Extracted textual features using **TF-IDF** and **Word2Vec**.
* Implemented **Support Vector Machine**, **Random Forest**, and **LSTM** models.
* Evaluated each model using multiple classification metrics for performance comparison.

The experiments demonstrate how different feature extraction techniques and classification algorithms influence sentiment classification performance.

---

# 🚀 Installation

Clone repository

```bash
git clone https://github.com/yourusername/free-fire-sentiment-analysis.git
```

Move into project

```bash
cd free-fire-sentiment-analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Project

## Step 1

Run

```text
Free_Fire_Scraping.ipynb
```

to collect review data.

## Step 2

Run

```text
Sentiment_Analysis_Training.ipynb
```

to:

* preprocess data
* train models
* evaluate performance
* compare results

---

# 📦 Requirements

Major dependencies include:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* tensorflow
* keras
* nltk
* gensim
* sastrawi
* google-play-scraper

---

# 💡 Future Improvements

Future work may include:

* Fine-tuning IndoBERT
* Hyperparameter Optimization
* Cross Validation
* FastText Embedding
* Streamlit Deployment
* Flask REST API
* Real-time Sentiment Dashboard

---

# 👨‍💻 Author

**Shah Firizki Azmi**

Bachelor of Informatics

Universitas Ahmad Dahlan

---

# 📄 License

This project is intended for educational and research purposes.
