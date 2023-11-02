# Customer-Reviews-Sentiment-Analysis

# Sentiment Analysis on Amazon Musical Instruments Reviews

**Overview**
This repository contains a Sentiment Analysis Mini Project focused on Amazon Musical Instruments Reviews. Sentiment analysis is a valuable natural language processing (NLP) technique with profound implications for business development, as it provides invaluable insights into customer opinions. In this project, we explore the Amazon Musical Instruments Reviews dataset, perform exploratory data analysis (EDA), and build a sentiment analysis model.

Project Structure
The project is structured into the following sections:

Dataset:

The dataset used in this project is sourced from Kaggle, available in JSON and CSV formats. We utilize the CSV format for our analysis. The dataset comprises customer feedback on musical instruments purchased from Amazon.
Data Preprocessing:

Checking for Null Values
Filling Missing Values
Concatenating 'reviewText' and 'summary' Columns
Statistical Description of the Dataset
Labeling Products Based on Ratings Given
Text Preprocessing:

Text Cleaning
Text Processing
Applying Text Processing Functions
Exploratory Data Analysis (EDA):

Overview of the Dataset
Analysis of Polarity, Review Length, and Word Counts
N-Gram Analysis
Word Clouds for Reviews with Positive, Neutral, and Negative Sentiments
Feature Engineering:

Dropping Insignificant Columns
Encoding the Target Variable
TF-IDF Vectorizer
Resampling the Dataset
Model Selection and Evaluation:

Trying various classification models
K-Fold Cross Validation
Hyperparameter Tuning
Identifying the Best Model
Metrics Evaluation, including Confusion Matrix and Classification Scores
Conclusion:

Dataset Insights:
Discussing important features for sentiment analysis
Reconsidering the removal of stopwords
Model Insights:
Selecting the best-performing model
Performance on the test set
Considering alternative cross-validation methods and data scaling
Usage
To replicate this project, follow these steps:

Dataset:

Download the dataset from Amazon Musical Instruments Reviews on Kaggle.
Use the CSV format of the dataset for analysis.
Environment Setup:

Create a Python environment with the necessary libraries (e.g., Pandas, NumPy, Scikit-Learn, Matplotlib, and NLTK).
Project Execution:

Execute the Jupyter Notebook for each section, following the project's structure.
Conclusion
Sentiment analysis is a powerful tool for extracting insights from customer reviews. This project explores sentiment analysis on Amazon Musical Instruments Reviews, provides data preprocessing, text analysis, and model selection insights. The results suggest that logistic regression is the best-performing model for sentiment analysis, with potential for further improvements in cross-validation and data scaling.

Feel free to adapt and extend this project to explore other datasets and applications of sentiment analysis in NLP.
