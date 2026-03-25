BBC News Topic Classifier (NLP)
An automated Machine Learning system that reads news articles and instantly categorizes them into five major topics. This project demonstrates Natural Language Processing (NLP) and Multi-class Classification using Python.

Project Overview
This project uses a Multinomial Naive Bayes model to analyze the vocabulary of news stories. It distinguishes between different types of news by identifying key patterns and word frequencies within the text.

The model classifies news into 5 categories:

Business
Entertainment
Politics
Sport
Tech

Tech Stack
Language: Python 3.x

Libraries:
Pandas (Data manipulation)
Scikit-Learn (Machine Learning and NLP)
Algorithm: Multinomial Naive Bayes

Dataset: BBC News Archive (2,225 articles)

Key Features
Automated Text Cleaning: Handles missing values and NaN errors to ensure the model runs reliably.
Stop-Word Removal: Filters out common English words (like "the", "a", "is") to focus on meaningful keywords.
ML Pipeline: Uses a clean Scikit-Learn Pipeline for professional, readable code.
Instant Prediction: Includes a testing section to verify new headlines in real-time.

File Structure

BBC_News_Classifier.ipynb: The main Jupyter Notebook containing the code.
bbc-news-data.csv: The dataset used for training and testing.
requirements.txt: List of necessary Python libraries.

Performance
The model achieves high accuracy by focusing on domain-specific keywords (e.g., "shares" for Business, "coach" for Sport). It is optimized for speed and works exceptionally well with short text inputs.

How to Use
Clone this repository to your local machine.
Open the .ipynb file in Google Colab or Jupyter Notebook.
Run all cells to train the model and see the predictions.
