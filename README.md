# Customer Reviews Sentiment Analysis

This project performs **Sentiment Analysis on customer reviews** using **TF-IDF vectorization** and **Logistic Regression**.  
It demonstrates **text preprocessing**, **model training**, **evaluation**, and **prediction** on new reviews.

---

## 📌 Features

- Clean and preprocess text: lowercase, punctuation removal, and whitespace normalization.
- Convert text into numerical features using **TF-IDF Vectorization**.
- Train a **Logistic Regression** model to classify reviews as `positive` or `negative`.
- Evaluate model performance with:
  - Accuracy
  - Classification Report (Precision, Recall, F1-score)
  - Confusion Matrix
- Make predictions on new customer reviews.

---

## 📂 Dataset

The dataset `customer_reviews.csv` contains two columns:

| review | sentiment |
|--------|-----------|
| The product is amazing! Exceeded my expectations. | positive |
| Very bad quality, broke after one use. | negative |
| Excellent service and fast delivery. | positive |
| I am disappointed, the item arrived late. | negative |

- `review` → The text of the customer review.  
- `sentiment` → The label: `positive` or `negative`.  

> You can upload your own CSV with similar format in Google Colab or Jupyter.

---

## 🛠 Installation

```bash
pip install pandas scikit-learn matplotlib joblib
