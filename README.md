# ReviewGuard: Explainable Fake Product Review Detection

## Overview

ReviewGuard is an NLP-based machine learning system that detects fraudulent product reviews on e-commerce platforms. The project uses TF-IDF feature extraction and Logistic Regression to classify reviews as Fake or Genuine.

## Problem Statement

Online marketplaces often suffer from fake reviews that mislead customers and affect recommendation quality. This project aims to automatically identify suspicious reviews and generate a trust score.

## Dataset

* Fake Reviews Dataset (Kaggle)
* 40,432 labeled reviews
* Classes:

  * CG (Fake Reviews)
  * OR (Genuine Reviews)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* NLP
* TF-IDF
* Logistic Regression

## Methodology

1. Data Cleaning
2. Text Preprocessing
3. TF-IDF Vectorization
4. Train-Test Split
5. Logistic Regression Training
6. Performance Evaluation
7. Trust Score Generation

## Results

* Accuracy: 86.5%
* Precision: 86.7%
* Recall: 86.5%
* F1-Score: 86.5%

## Future Improvements

* BERT-based Classification
* Deep Learning Models
* Real-time Web Application
* Explainable AI Dashboard
