# tweet-classification

# Tweet Classification: Hate Speech and Offensive Language Detection



## Project Overview

This project involves building a machine learning pipeline to classify tweets into three categories:
1. **Hate Speech (0)**
2. **Offensive Language (1)**
3. **Neutral (2)**

The goal is to accurately detect hate speech and offensive language in tweets to promote healthier online interactions.

## Features

- **Data Cleaning & Preprocessing**: Text normalization, removal of URLs, punctuation, stopwords, and lemmatization.
- **Feature Engineering**: TF-IDF vectorization and dimensionality reduction using Truncated SVD.
- **Model Training & Evaluation**: Training multiple classifiers (Logistic Regression, Random Forest, SVM, Decision Tree) with cross-validation and hyperparameter tuning.
- **Model Deployment**: Saving and loading pipeline components for making predictions on new data.
- **Comprehensive Reporting**: Detailed analysis and results available in the project report.

## Dataset

The dataset used in this project is the [Hate Speech and Offensive Language Dataset](https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset) by Davidson et al. It contains tweets labeled as Hate Speech, Offensive Language, or Neither.

**Dataset File**: `data/raw/hate_speech_and_offensive_language_dataset.csv`

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository or download the file**

   ```bash
   git clone https://github.com/yourusername/tweet-classification.git
   cd tweet-classification
