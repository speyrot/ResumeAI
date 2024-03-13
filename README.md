# Ethical AI Resume Matcher

## Project Overview

The Ethical AI Resume Matcher is designed to automate the process of matching job seekers' resumes with relevant job postings. Utilizing advanced machine learning techniques, this project aims to reduce biases traditionally encountered in the hiring process, promoting a fairer job market.

## Features

- **Bias-Free Matching**: Leverages a dataset of resumes and job postings to train a machine learning model that prioritizes skills and experience over potentially biased factors.
- **High Accuracy**: Incorporates text classification algorithms, including RandomForest and SVM, with extensive feature engineering to ensure high accuracy in matching.
- **Scalability**: Designed to handle a large number of resumes and job postings, making it suitable for both small businesses and large corporations.

## Dataset

The dataset includes a collection of resumes across various job categories, sourced from public datasets on platforms like Kaggle. Each resume has been anonymized and categorized to ensure privacy and relevance.

## Model Development

The project employs a RandomForest classifier, optimized with TF-IDF vectorization and SMOTE for handling class imbalance, achieving a notable accuracy in preliminary tests. Additionally, experimentation with SVM models was conducted for comparative analysis.

### Key Components

- **TF-IDF Vectorization**: Converts text data into a format suitable for machine learning model training, with the inclusion of bi-grams and tri-grams to capture more contextual information.
- **SMOTE**: Addresses class imbalance in the training dataset, ensuring the model learns equally from all categories.
- **RandomForest Classifier**: Chosen for its high accuracy and flexibility, further optimized through hyperparameter tuning.
- **SVM Experimentation**: Served as an alternative approach for comparison, highlighting the effectiveness of RandomForest in this application.

