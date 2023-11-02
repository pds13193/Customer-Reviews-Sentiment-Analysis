# Sentiment Analysis on Amazon Musical Instruments Reviews

**Overview**

This repository contains a Sentiment Analysis Mini Project focused on Amazon Musical Instruments Reviews. Sentiment analysis is a valuable natural language processing (NLP) technique with profound implications for business development, as it provides invaluable insights into customer opinions. In this project, we explore the Amazon Musical Instruments Reviews dataset, perform exploratory data analysis (EDA), and build a sentiment analysis model.

**Project Structure**

The project is structured into the following sections:

**Dataset**

The dataset used in this project is sourced from Kaggle, available in JSON and CSV formats. We utilize the CSV format for our analysis. The dataset comprises customer feedback on musical instruments purchased from Amazon.

**Data Preprocessing**
1. Checking for Null Values
2. Filling Missing Values
3. Concatenating 'reviewText' and 'summary' Columns
4. Statistical Description of the Dataset
5. Labeling Products Based on Ratings Given

**Text Preprocessing**
1. Text Cleaning
2. Text Processing
3. Applying Text Processing Functions
  
**Exploratory Data Analysis (EDA)**
1. Overview of the Dataset**
2. Analysis of Polarity, Review Length, and Word Counts
3. N-Gram Analysis
4. Word Clouds for Reviews with Positive, Neutral, and Negative Sentiments

**Feature Engineering**
1. Dropping Insignificant Columns
2. Encoding the Target Variable
3. TF-IDF Vectorizer
4. Resampling the Dataset

**Model Selection and Evaluation**

1. Trying various classification models**
2. K-Fold Cross Validation
3. Hyperparameter Tuning
4. Identifying the Best Model
5. Metrics Evaluation, including Confusion Matrix and Classification Scores

# Usage

**To replicate this project, follow these steps:**

**Dataset:**
Use the dataset available in the repository

**Environment Setup:**
Create a Python environment with the necessary libraries - Pandas, NumPy, Scikit-Learn, Matplotlib, and NLTK

**Project Execution:**
Execute the Jupyter Notebook for each section, following the project's structure.

**Conclusion**

Sentiment analysis is a powerful tool for extracting insights from customer reviews. This project explores sentiment analysis on Amazon Musical Instruments Reviews, provides data preprocessing, text analysis, and model selection insights. The results suggest that logistic regression is the best-performing model for sentiment analysis, with potential for further improvements in cross-validation and data scaling.

Feel free to adapt and extend this project to explore other datasets and applications of sentiment analysis in NLP.
