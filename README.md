# Sentiment Analysis with NLP

This project demonstrates **Sentiment Analysis using Natural Language Processing (NLP)**.  
It covers **text preprocessing**, **vectorization**, **model training**, and **evaluation** using Python, scikit-learn, and NLTK.

---

## 📌 Features

- Preprocess text data: lowercase, punctuation removal, tokenization, stopword removal, and lemmatization.
- Vectorize text using **TF-IDF**.
- Train a **Logistic Regression** classifier to predict sentiment.
- Evaluate the model using accuracy, classification report, and confusion matrix.
- Predict sentiment for custom input sentences.

---

## 📂 Dataset

- By default, the notebook uses **NLTK’s movie_reviews dataset** (binary positive/negative labels).  
- You can also use a **custom CSV file** with two columns:
  - `text`: The review text
  - `label`: Sentiment (`positive` / `negative`)

Example CSV format:

| text                                         | label    |
|---------------------------------------------|----------|
| The movie was fantastic!                     | positive |
| The plot was dull and predictable.          | negative |

---

## 🛠️ Installation

```bash
# Install required libraries
pip install nltk scikit-learn pandas matplotlib
