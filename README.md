# part-3-nlp-sequence-modeling

## Overview
This project performs text classification on customer support messages using Natural Language Processing (NLP) techniques.

The project includes:
- Dataset understanding
- Text preprocessing
- Text vectorization using TF-IDF
- Baseline model using Logistic Regression
- Sequence model architecture using LSTM
- Attention and Transformer reflection

---

## Dataset
Dataset used:
- `customer_support_text_classification.csv`

Target classes:
- Positive
- Negative
- Neutral

---

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras

---

## Tasks Performed

### Task 1: Dataset Understanding
- Number of records
- Class distribution
- Average text length
- Sample text records

### Task 2: Text Preprocessing
- Lowercasing
- Removing special characters
- Tokenization
- Stopword removal
- Padding sequences

### Task 3: Text Vectorization
- TF-IDF vectorization

### Task 4: Baseline Model
- Logistic Regression model
- Accuracy evaluation
- Confusion matrix
- Classification report

### Task 5: Sequence Model
- LSTM architecture design

### Task 6: Attention and Transformer Reflection
- RNN limitations
- LSTM memory handling
- Attention mechanism
- Transformer importance

---

## Repository Structure

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
