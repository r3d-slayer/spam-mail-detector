# Spam Mail Detector using BERT

A deep learning–based spam detection system built using **BERT (Bidirectional Encoder Representations from Transformers)** for binary email classification.

This project fine-tunes a pretrained transformer model to classify emails as:

- **Spam (1)**
- **Ham / Not Spam (0)**

---

##  Overview

Traditional spam filters (Naive Bayes, Logistic Regression, SVM) rely on keyword frequency and shallow text patterns. While efficient, they often fail to capture contextual meaning.

This project uses **BERT**, a transformer-based model that understands semantic context and word relationships, leading to improved classification performance.

---

##  Model Details

- **Base Model:** `bert-base-uncased`
- **Task:** Binary Text Classification
- **Framework:** TensorFlow (TFBertForSequenceClassification)
- **Tokenizer:** BERT Tokenizer
- **Output Layer:** Dense layer with Softmax/Sigmoid activation

### Training Pipeline

1. Load dataset  
2. Text preprocessing  
3. Tokenization using BERT tokenizer  
4. Train-validation split  
5. Fine-tuning BERT  
6. Evaluation using classification metrics  
