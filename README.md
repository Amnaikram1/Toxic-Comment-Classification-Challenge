# Toxic Comment Classification Challenge with TF-IDF

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Vectorization](#vectorization)
- [Model Comparison](#model-comparison)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Introduction
The project identifies and calculates the probability score of online toxic comments for each of six given categories: 'toxic', 'severe_toxic', 'obscene', 'threat', 'insult', 'identity_hate'.

## Installation
To install and run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/Toxic-Comment-Classification-Challenge.git
   cd Toxic-Comment-Classification-Challenge
   ```

## Usage
Load the data files of training and test sets using the `read_csv` module of the pandas library.

## Exploratory Data Analysis
The training data has 7 columns: `comment_text` and six labels.
The data is cleaned using the `re` library.

## Vectorization
The `comment_text` column is vectorized using the Term Frequency-Inverse Document Frequency (TF-IDF) algorithm.

## Model Comparison
The logistic regression model outperformed Support Vector Machines, Multi-layer Perceptron, and MiniLM models of Sentence Transformers.

| Model                     | Leaderboard Score |
|---------------------------|-------------------|
| Logistic Regression       | 0.97461           |
| Support Vector Machines   | 0.8242            |
| Multi-layer Perceptron    | 0.9092            |
| Sentence Transformers     | 0.9596            |

## Acknowledgments
- The Scikit-Learn library and its contributors
- Kaggle for providing the Toxic Comment Classification Challenge
- The open-source community for their invaluable contributions

---

This version corrects the grammatical and formatting errors in your original text and ensures consistency in style.
