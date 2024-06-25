Spam Comments Detection Using Machine Learning
Overview
Spam comments on social media platforms are often used to redirect users to other accounts, websites, or content. Detecting these spam comments is crucial for maintaining the quality and integrity of online interactions. This project focuses on developing a machine learning model to classify YouTube comments as either spam or not spam using a dataset of YouTube spam comments. The project employs the Bernoulli Naive Bayes algorithm for binary classification.

Dataset
The dataset used in this project is sourced from Kaggle and contains YouTube comments labeled as spam or not spam. Each entry in the dataset includes:

COMMENT_ID: Unique identifier for the comment
AUTHOR: Name of the comment author
DATE: Date the comment was posted
CONTENT: The actual text of the comment
CLASS: Label indicating whether the comment is spam (1) or not spam (0)

Project Structure
Youtube01-Psy.csv: The dataset file containing YouTube comments and their respective labels.
spam_comments_detection.py: Python script containing the entire code for the project.
README.md: Detailed description of the project (this file).

Dependencies
pandas: For data manipulation and analysis.
numpy: For numerical operations.
sklearn: For machine learning algorithms and data preprocessing.
CountVectorizer: For converting text data into numerical vectors.
train_test_split: For splitting the dataset into training and testing sets.
BernoulliNB: For the Naive Bayes classification algorithm.

