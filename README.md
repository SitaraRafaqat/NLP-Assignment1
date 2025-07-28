# NLP-Assignment1:

# 📊 NLP Assignment – SMS Spam Detection

This project implements an NLP classification pipeline to detect spam messages in SMS texts. It uses both traditional machine learning models and different feature engineering techniques (BOW, TF-IDF, Word2Vec).

## Dataset

- **Source:** UCI SMS Spam Collection Dataset
- **Labels:** 
  - `ham` → non-spam message  
  - `spam` → unwanted promotional/fraudulent message

---

## Models Trained

| Model                    | Features      |
|-------------------------|---------------|
| Multinomial Naïve Bayes | BOW, TF-IDF   |
| Logistic Regression      | BOW, TF-IDF, Word2Vec |
| Linear SVM              | TF-IDF        |

---

## Key Features

- **Text Preprocessing:** lowercasing, regex, tokenization, stopword removal, lemmatization
- **Vector Representations:** Bag-of-Words, TF-IDF, Word2Vec
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score (macro)
- **Reproducibility:** Random seeds fixed, requirements file included

---

##  Requirements

Install packages with:

```bash
pip install -r requirements.txt
