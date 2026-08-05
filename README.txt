# Twitter Sentiment Analysis using Linear SVM

## Overview

This project implements a Twitter Sentiment Analysis system that classifies tweets as **Positive** or **Negative** using Natural Language Processing (NLP) and Machine Learning techniques. The model is trained on the **Sentiment140** dataset containing over **1.6 million tweets** and leverages **TF-IDF vectorization** with a **Linear Support Vector Machine (SVM)** classifier for robust text classification.

---

## Features

- Binary sentiment classification of tweets
- Comprehensive NLP preprocessing pipeline
  - Text cleaning
  - Tokenization
  - Stop word removal
  - Lemmatization
- TF-IDF feature extraction
- Linear SVM classifier
- Performance evaluation using
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC Score
  - Confusion Matrix
- Prediction on custom user input tweets

---

## Dataset

This project uses the **Sentiment140** dataset.

- **Training Samples:** 1,600,000 Tweets
- **Task:** Binary Sentiment Classification
- **Classes**
  - 0 → Negative
  - 4 → Positive (converted to 1)

Dataset Link

https://www.kaggle.com/datasets/kazanova/sentiment140

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

---

## Project Workflow

```
Raw Tweets
      │
      ▼
Text Cleaning
      │
      ▼
Tokenization
      │
      ▼
Stop Word Removal
      │
      ▼
Lemmatization
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Linear SVM Classifier
      │
      ▼
Sentiment Prediction
```

---

## Model Evaluation

The trained model is evaluated using the following classification metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Project Structure

```
Twitter-Sentiment-Analysis/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── sentiment_analysis.ipynb
│
├── models/
│   ├── svm_model.pkl
│   └── tfidf_vectorizer.pkl
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/twitter-sentiment-analysis.git
```

Move into the project directory

```bash
cd twitter-sentiment-analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

Place the training and testing datasets inside the **data** folder.

Run the notebook

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

Open the notebook and execute all cells sequentially.

---

## Results

The Linear SVM model demonstrates strong performance on large-scale Twitter sentiment classification by effectively handling sparse, high-dimensional TF-IDF features. The project showcases an end-to-end NLP pipeline, from preprocessing to model evaluation and prediction.

---

## Future Improvements

- Fine-tune transformer models such as BERT or RoBERTa
- Multi-class sentiment classification
- Hyperparameter optimization
- Real-time Twitter sentiment prediction
- Web application deployment using Flask or Streamlit

---

## Author

**Aditya**