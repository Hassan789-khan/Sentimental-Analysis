# Sentimental-Analysis
This repository contains the implementation of Sentiment Analysis using a reviews dataset. The task was completed as part of my internship at Developers Hub, focusing on text preprocessing, vectorization, and classification models to determine the sentiment of customer reviews.
📁 Dataset Overview
Total Records: 50,000
Columns:
review – Text of the customer review
sentiment – Sentiment label (positive or negative)
Data Quality:
No missing values
No duplicate entries
Balanced classes (25,000 positive and 25,000 negative)
🧹 Data Preprocessing
Text Cleaning:
Lowercasing
Removing special characters & punctuation
Tokenization
Stop words removal
Lemmatization
Feature Extraction:
TF-IDF Vectorization was used to convert text data into numerical features while emphasizing important terms.
🤖 Model Building
Trained and compared the performance of the following classifiers:
Logistic Regression
Naive Bayes
SGD Classifier (used as an SVM alternative)
Each model was evaluated on accuracy and general performance to identify the most effective approach.
📊 Key Findings
The dataset was clean and well-balanced, ideal for binary classification.
Preprocessing steps significantly improved text quality and model learning.
TF-IDF helped highlight words most relevant to sentiment classification.
All three models showed promising results, with room for improvement through tuning.
🛠️ Tools & Technologies
Python
Pandas
Scikit-learn
NLTK / spaCy
Matplotlib / Seaborn
