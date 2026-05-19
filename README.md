# NLP Book Review Analysis & Rating Prediction

This project explores Natural Language Processing (NLP) techniques on a large-scale dataset of book reviews (~357,000 reviews). The objective was to predict reader satisfaction ratings from textual reviews and analyze customer preferences using modern NLP and machine learning approaches.

The project was completed as part of the *Advanced Topics in Machine Learning* course at the University of Geneva.

---

## Project Objectives

The project was divided into two main tasks:

### 1. Rating Prediction

Build predictive models capable of estimating book ratings (from 1 to 5) based on review text.

Different NLP approaches were compared, including:

* Bag of Words (BoW)
* TF-IDF
* Logistic Regression
* Hyperparameter tuning with GridSearchCV
* Bidirectional LSTM networks
* Transformer-based embeddings

### 2. NLP Recommendation & Topic Analysis

Analyze what readers generally like or dislike and build a recommendation-oriented NLP pipeline.

This included:

* Topic modeling with BERTopic
* Semantic embeddings using Sentence Transformers
* UMAP dimensionality reduction
* HDBSCAN clustering
* Review similarity analysis and recommendation logic

---

## Dataset

The dataset contains:

* Book reviews
* Reader ratings
* Book metadata (title, description, categories, authors, etc.)

The original dataset was provided through a Kaggle competition hosted for the course.

### Dataset Links

Kaggle competition:
https://www.kaggle.com/competitions/atml-unige-2025

Competition access page:
https://www.kaggle.com/t/434f76a47f384c019ca79fc4720f042c

Note: Access may require joining the competition or having a Kaggle account.

---

## Technologies Used

* Python
* Pandas / NumPy
* Scikit-learn
* TensorFlow / Keras
* HuggingFace Transformers
* BERTopic
* Sentence Transformers
* Matplotlib / Seaborn

---

## Key Results

| Model                              | MAE    |
| ---------------------------------- | ------ |
| Bag of Words + Logistic Regression | 0.6548 |
| TF-IDF + Logistic Regression       | 0.5952 |
| Tuned TF-IDF Model                 | 0.5467 |

The project demonstrates how both classical NLP approaches and modern deep learning architectures can be applied to large-scale textual datasets for prediction and semantic analysis.

---

## Authors

* Rachel Rieille
* Ahmad Hamad
* Bogdan Secas
* Eva Battolla
