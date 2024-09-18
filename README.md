Disaster Tweet Classification

This project classifies tweets to determine if they are about real disasters or not using Natural Language Processing (NLP) techniques. The model was built for the Kaggle competition: Natural Language Processing with Disaster Tweets.

Project Overview
In this project, tweets are analyzed and classified into two categories:

Disaster-related tweets (1): Tweets talking about real disasters.
Non-disaster-related tweets (0): Tweets that do not mention real disasters.
Key Highlights:
Dataset: Tweets from the competition with text, keyword, location, and target labels
Algorithm: RandomForest, Logistic Regression
Metric: F1 Score (Achieved: 0.7842)

Technologies Used
Python: Main programming language
Libraries:
pandas, numpy for data manipulation
scikit-learn for model building
nltk, re for text preprocessing
Tools: Jupyter Notebooks, Google Colab

Model Evaluation
The final model was evaluated using the F1 score due to the imbalanced dataset. The project achieved a 0.7842 F1 score on the test set
