Sentiment Analysis on Movie Reviews

This project aims to develop a machine learning-based system for sentiment analysis of movie reviews, classifying them as positive, negative, or neutral.

Overview:

Sentiment analysis is the process of automatically determining the sentiment expressed in text data. This project focuses on analyzing movie reviews to classify their sentiment polarity. The motivation is to provide a tool for movie studios, marketers, and researchers to analyze public opinion about movies efficiently.

Dataset:

The dataset used in this project is the IMDB movie review dataset, consisting of 25,000 movie reviews evenly split between positive and negative sentiments. The dataset is available through the Keras datasets module in Python.

Methodology:

The methodology involves the following steps:

1. Data Preprocessing: Removing punctuation, converting text to lowercase, removing stop words, and stemming.
2. Feature Extraction: Using TF-IDF vectorization to convert text data into numerical features.
3. Model Training: Training Naive Bayes and Logistic Regression models on the preprocessed data.
4. Model Evaluation: Evaluating model performance using accuracy, confusion matrix, F1 score, and recall score.

Results:

- Naive Bayes Classifier:
  - Accuracy: 85%
  - F1 Score: 0.85
  - Recall Score: 0.85

- Logistic Regression Classifier:
  - Accuracy: 88%
  - F1 Score: 0.88
  - Recall Score: 0.88

The Logistic Regression classifier outperformed the Naive Bayes classifier, but both achieved high accuracy. Visualizations of confusion matrices and ROC curves are provided in the report.

Limitations and Future Work:

- Language and domain-specific limitations
- Difficulty in identifying sarcasm and tone
- Dependence on quality and size of training data
- Generalization to unseen data

Future work could explore more granular sentiment classifications, evaluate performance on different text data types, and consider ethical and social implications.

Conclusion:

This project demonstrates the effectiveness of machine learning algorithms for sentiment analysis of movie reviews. The techniques and tools used can be extended to other domains and applications for sentiment analysis.[1]

