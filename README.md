# AI-Generated Text Detection using Machine Learning and Deep Learning

## Overview

This project was developed during a Machine Learning Research Internship at NIT Patna. The system performs binary classification to distinguish between AI-generated and human-written text using both traditional machine learning algorithms and deep learning models.

## Features

* AI vs Human text classification
* TF-IDF based NLP preprocessing
* Multiple ML model comparison
* LSTM-based deep learning architecture
* ROC Curve and Confusion Matrix evaluation
* Performance visualization

## Dataset

* 200K+ text samples
* Human-written and AI-generated content
* Sources include GPT-2, GPT-3, GPT-J, and ChatGPT
* Dataset obtained from HuggingFace

## Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Matplotlib

## Models Implemented

### Machine Learning Models

* Naive Bayes
* Random Forest
* Decision Tree
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Logistic Regression

### Deep Learning

* Long Short-Term Memory (LSTM)

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 96.4%    |
| SVM                 | 96.4%    |
| LSTM                | 99.0%    |

The LSTM model achieved the best overall performance with strong generalization and low misclassification.

## Internship

Machine Learning Research Internship — NIT Patna (2025)

## Repository Structure

```text
ai-generated-text-detection/
│
├── code/
├── report/
├── results/
├── README.md
├── requirements.txt
└── .gitignore
```
