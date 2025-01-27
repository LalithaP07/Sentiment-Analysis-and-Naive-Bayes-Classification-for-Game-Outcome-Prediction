# Sentiment-Analysis-and-Naive-Bayes-Classification-for-Game-Outcome-Prediction
This project focuses on analyzing tweets related to NBA teams and predicting game outcomes using sentiment analysis and a Naive Bayes classification model.
oject Description
Data Collection: Extracted and preprocessed tweets associated with specific NBA teams (e.g., "Thunder") using game dates and results.
Sentiment Analysis: Utilized the VADER SentimentIntensityAnalyzer to clean tweets by removing URLs, team names, and calculating sentiment scores.
Classification: Implemented a Naive Bayes classification pipeline with TF-IDF vectorization to classify game outcomes into "Win" (W) or "Lose" (L) categories.

Achievements:

Dataset:
Processed tweets related to game outcomes, with 9 labeled instances for training and testing.
Tweets were cleaned to remove noise (URLs, team names) for better model performance.
Model Performance:

Naive Bayes Classifier:
Precision: 50% for predicting "Win" outcomes.
Recall: 80% for correctly identifying "Win" outcomes.
F1-Score: 62% for "Win" predictions.
The model achieved an average accuracy of 44%.
Results demonstrate potential for refining models and increasing dataset size to improve classification performance.
Efficiency:
Integrated tweet preprocessing, sentiment analysis, and game outcome labeling in a single streamlined pipeline.
Leveraged TF-IDF vectorization to capture the importance of unique words in tweets effectively.
Reproducibility:
Modularized code with clear blocks for preprocessing, sentiment analysis, and model training.
Provided detailed output for debugging and analysis, ensuring transparency in the pipeline's results.
This project provides a baseline approach to leveraging sentiment analysis for sports analytics, demonstrating the effectiveness of Naive Bayes classifiers with TF-IDF for predicting game outcomes.







