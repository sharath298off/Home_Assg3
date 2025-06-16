# Home_Assg3
# 🧠 CS5720 – Neural Networks and Deep Learning  
## 📝 Home Assignment 3 – Summer 2025  
**University of Central Missouri**  
**Student Name:** sharath chandra Seriyala(700776646)

---

## 📚 Assignment Overview

This repository contains solutions for Home Assignment 3, covering:

1. **LSTM-based Text Generation** (RNN)
2. **NLP Preprocessing** (Tokenization, Stopword Removal, Stemming)
3. **Named Entity Recognition using spaCy**
4. **Scaled Dot-Product Attention Mechanism**
5. **Sentiment Analysis using HuggingFace Transformers**

---

## ✅ Task Summary

### Q1: LSTM for Text Generation
- Trained a character-level LSTM model on Shakespeare text.
- Used `tf.keras` to build and train the model.
- Generated new text using temperature-based sampling.

### Q2: NLP Preprocessing Pipeline
- Tokenized input text without using `punkt`.
- Removed stopwords using `nltk`.
- Applied stemming with `PorterStemmer`.

### Q3: Named Entity Recognition (NER)
- Used `spaCy` to extract named entities.
- Printed entity, label (PERSON, DATE, etc.), and character positions.

### Q4: Scaled Dot-Product Attention
- Implemented attention with `Q`, `K`, and `V` matrices using NumPy.
- Applied softmax to scaled dot products.
- Output attention weights and final result.

### Q5: Sentiment Analysis with HuggingFace
- Used the `transformers` pipeline to analyze sentiment of a sentence.
- Printed predicted label and confidence score.
