# PRODIGY_DS_04
It is a  fourth task of my internship.
This repository contains code for performing sentiment analysis on textual data using Python libraries such as NLTK's Vader for sentiment analysis and Pandas for data manipulation. 

Overview sentiment_analysis(Task04).ipynb: This Python script demonstrates how to conduct sentiment analysis on a dataset using NLTK's Vader sentiment intensity analyzer and Pandas DataFrame for data management. Modify the sample data in the script or replace it with your own dataset. Run the script to perform sentiment analysis and visualize the sentiment scores. Sample Data The sample data used in this script includes:
ID: Unique identifier for each entry. Topic: The topic or category of the text. Sentiment: Initially labeled sentiment (Positive/Neutral) which is later replaced with sentiment scores. Text: Textual content for sentiment analysis. Sentiment Analysis Process Data is loaded into a Pandas DataFrame. NLTK's Vader SentimentIntensityAnalyzer is initialized. Sentiment analysis is performed on the text data using Vader, and sentiment scores (compound score) are added to the DataFrame. The sentiment scores are plotted against the index to visualize the sentiment trends. Files sentiment_analysis.py: Python script for sentiment analysis. requirements.txt: List of required libraries. Feel free to explore and modify the code for your own sentiment analysis tasks or as part of learning NLTK and Pandas for text analysis projects.

The sample data used in this script includes:
ID: Unique identifier for each entry.
Topic: The topic or category of the text.
Sentiment: Initially labeled sentiment (Positive/Neutral) which is later replaced with sentiment scores.
Text: Textual content for sentiment analysis.
Sentiment Analysis Process
Load Data: Data is loaded into a Pandas DataFrame.
Initialize Analyzer: NLTK's Vader SentimentIntensityAnalyzer is initialized.
Perform Analysis: Sentiment analysis is performed on the text data using Vader, and sentiment scores (compound score) are added to the DataFrame.
Visualize Results: The sentiment scores are plotted against the index to visualize sentiment trends.
