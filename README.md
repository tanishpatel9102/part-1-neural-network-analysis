# NLP Sequence Modeling Project

## Project Overview

This project focuses on building a Natural Language Processing (NLP) pipeline for customer support sentiment classification. The goal is to understand how text data is converted into numerical representations and how traditional NLP approaches compare with sequence-based deep learning models.

The project includes text preprocessing, vectorization techniques, baseline machine learning models, sequence models such as LSTM, and conceptual understanding of attention and transformers.

---

## Dataset Information

Dataset Used:
- Customer Support Text Classification Dataset

Target Column:
- sentiment_label

Classes:
- Positive
- Neutral
- Negative

Input Feature:
- customer_message

Additional Features:
- channel
- word_count
- urgent_flag

---

## Objectives

The main objectives of this project are:

- Understand NLP preprocessing techniques
- Convert text into vectors
- Build baseline NLP models
- Explore sequence-based deep learning models
- Understand attention and transformer architectures

---

# Project Structure

```text
part-3-nlp-sequence-modeling/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
│
└── results/
    ├── model_evaluation.csv
    └── sample_predictions.txt
```

---

# Tasks Performed

## Task 1: Dataset Understanding

Performed exploratory analysis including:

- Number of records
- Target classes
- Sample text messages
- Average text length
- Class distribution

---

## Task 2: Text Preprocessing

Preprocessing steps included:

- Lowercasing
- Removing special characters
- Tokenization
- Stopword removal
- Sequence padding

Libraries Used:
- NLTK
- Regex

---

## Task 3: Text Vectorization

Implemented text vectorization using:

### TF-IDF Vectorization
Traditional NLP approach converting text into weighted numerical vectors.

### Tokenizer-Based Sequences
Sequence-based approach converting words into integer sequences for deep learning models.

---

## Task 4: Baseline Model

Built a baseline model using:

- TF-IDF Vectorization
- Logistic Regression

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Task 5: Sequence Model

Implemented a simple LSTM model consisting of:

- Embedding Layer
- LSTM Layer
- Dense Output Layer

The sequence model processes padded text sequences and learns contextual word relationships.

---

## Task 6: Attention and Transformer Reflection

Discussed:

- RNN limitations
- How LSTMs improve memory
- Attention mechanism
- Importance of transformers in modern NLP and Generative AI

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- NLTK
- Matplotlib

---

# Model Results

The baseline model achieved good classification performance using TF-IDF and Logistic Regression.

The LSTM sequence model demonstrated improved contextual understanding by processing text sequentially.

Detailed evaluation metrics are available in:

```text
results/model_evaluation.csv
```

Sample predictions are available in:

```text
results/sample_predictions.txt
```

---

# Conclusion

This project demonstrates the complete NLP workflow from preprocessing to sequence modeling. Traditional vectorization techniques such as TF-IDF provide strong baseline performance, while sequence models like LSTM improve contextual understanding of text.

Transformers and attention mechanisms further advance NLP capabilities and form the foundation of modern Generative AI systems.

---

# Future Improvements

Possible future enhancements include:

- Using GRU or Bidirectional LSTM
- Hyperparameter tuning
- Transformer-based models (BERT/GPT)
- Deployment using Flask or Streamlit
- Real-time sentiment prediction system

---

# Author

NLP Sequence Modeling Project
