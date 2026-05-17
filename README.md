# Twitter Emotion-Aware Sentiment Classification Using Machine Learning

## Project Overview

This project focuses on emotion-aware sentiment classification of Twitter text using Natural Language Processing (NLP) and Machine Learning techniques. The system preprocesses tweet data, extracts TF-IDF features, and applies multiple machine learning algorithms to classify sentiments from Twitter posts.

The project demonstrates the challenges of multi-class emotion and sentiment classification using real-world social media text data.

---

# Dataset

- **Dataset Name:** tweet_emotions.csv
- **Source:** Twitter Emotion Dataset
- **Type:** Text Classification Dataset

---

# Sentiment Classes

The original emotion labels were grouped into broader sentiment categories to improve classification performance:

| Original Emotions | Final Sentiment |
|---|---|
| Happiness, Love | Positive |
| Sadness, Worry | Negative |
| Neutral | Neutral |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK

---

# Machine Learning Models

The following machine learning algorithms were implemented and evaluated:

1. Naive Bayes
2. Support Vector Machine (SVM)
3. Logistic Regression

---

# NLP & Feature Engineering Techniques

- Text Cleaning
- Tokenization
- Stopword Removal
- Lemmatization
- TF-IDF Vectorization

---

# Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score

---

# Final Model Performance

| Model | Accuracy |
|---|---|
| Naive Bayes | 39.10% |
| SVM | 39.32% |
| Logistic Regression | 60.41% |

> Logistic Regression achieved the highest performance after sentiment grouping and TF-IDF optimization.

---

# Visualizations

## Accuracy Comparison

<img width="800" height="500" alt="Accuracy Graph" src="https://github.com/user-attachments/assets/8b22cb2d-69ac-4475-a371-e4af50de684e" />

---

## Confusion Matrix

<img width="1000" height="800" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/7579cdbd-3238-4c0e-b19d-c4a6230647a0" />

---

## ROC Curve

<img width="1000" height="800" alt="ROC Curve" src="https://github.com/user-attachments/assets/92d7c9df-05fc-4674-b9ac-7d95137062b4" />

---

# Key Findings

- Logistic Regression achieved the best overall performance.
- TF-IDF effectively converted textual data into numerical vectors.
- Sentiment grouping significantly improved classification accuracy.
- Multi-class emotion detection from Twitter text remains a challenging NLP task due to noisy and overlapping emotional expressions.

---

# Future Improvements

Possible future enhancements include:

- Deep Learning Models (LSTM, BERT)
- Word Embeddings (Word2Vec, GloVe)
- Balanced Datasets
- Transformer-based NLP Models

---

# Conclusion

This project successfully implemented an emotion-aware sentiment classification system using machine learning techniques. The results demonstrate the effectiveness of TF-IDF and Logistic Regression for Twitter sentiment classification while highlighting the challenges associated with real-world social media emotion analysis.
