# Natural-Language-Processing-NLP-

Twitter Sentiment Analysis
Welcome to the Twitter Sentiment Analysis project! This project focuses on analyzing sentiment in tweets related to the Malaysia General Election 15. By using advanced machine learning algorithms, I classify the sentiment of tweets into Positive, Neutral, and Negative categories.

Table of Contents
Project Overview
Dataset
Data Preprocessing
Exploratory Data Analysis
Modeling
Results
Conclusion
Installation
Usage
Contributing
License
Project Overview
The main objective of this project is to classify tweets related to the Malaysia General Election 15 period into Positive, Neutral, and Negative sentiments using advanced machine learning algorithms. The goal is to identify and track overall sentiment trends and patterns over the election period, providing a dynamic view of public opinion as events unfold.

Dataset
The dataset used in this project is a collection of tweets with sentiments labeled as Positive, Neutral, or Negative. It is loaded from a CSV file named TWSentiment.csv. The data was extracted 3 months before and 4 months after the Malaysia General Election 15.

Data Preprocessing
Loading Data: I load the dataset using pandas.
Data Cleaning: I replace sentiments in different languages to a consistent format (e.g., 'Negatif' to 'Negative').
Handling Missing Values: I drop rows with null values to clean the data.
Text Normalization: I preprocess the tweet texts by tokenizing, removing stopwords, and stemming.
Exploratory Data Analysis
Hot News about Malaysia: Extract and display tweets containing the keyword 'Malaysia'.
Data Duration: Calculate and display the duration over which the data was collected.
Visualizations:
Histogram of Compound Sentiment Scores
Histogram of Sentiment Distribution
Heatmap of Feature Correlations
Bar plot of Sentiment Counts after Cleaning Null Values
Hot News about Malaysia during General Election 15
I extracted tweets 3 months before and 4 months after the Malaysia General Election 15. The dataset includes significant public opinion trends during this period, highlighting major events and their impact on sentiment.

Modeling
Naive Bayes Classifier
Text Vectorization: Convert text data into numerical vectors using CountVectorizer.
Model Training: Train a Naive Bayes model on the training data.
Evaluation: Evaluate the model using accuracy, classification report, and confusion matrix.
Visualization: Plot confusion matrix for both training and test data.
Support Vector Machine (SVM)
TF-IDF Vectorization: Transform text data into TF-IDF vectors.
Model Training: Train an SVM model with a linear kernel.
Evaluation: Evaluate the model using accuracy, classification report, and confusion matrix.
Visualization: Plot confusion matrix for the test data.
Results
The models are evaluated on various metrics such as accuracy, precision, recall, and F1-score. Confusion matrices are used to visualize the performance of the models.

Conclusion
This project demonstrates the effectiveness of using machine learning techniques for sentiment analysis on Twitter data. During the Malaysia General Election 15 period, the analysis revealed:

7594 Negative tweets
4912 Positive tweets
3401 Neutral tweets
These results show a significant number of negative sentiments during the election period, indicating widespread public discontent as reflected on social media.


