# task4sentimentanalysis

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: POLU AKHILA

*INTERN ID*: CT04DZ2019

*DOMAIN*: DATA ANALYTICS

*DURATON*: 4 WEEKS

*MENTOR*: NEELA SANTOSH


This code performs sentiment analysis on a dataset of tweets using Natural Language Processing (NLP) and machine learning. It begins by importing the required Python libraries such as Pandas for data handling, Seaborn and Matplotlib for visualization, regular expressions (re) for text cleaning, and several Scikit-learn modules for preprocessing, model training, and evaluation. The dataset is loaded from a CSV file, and any rows with missing values in the text or sentiment columns are removed to ensure clean input. A text cleaning function is defined to preprocess the tweets by converting all text to lowercase, removing URLs, mentions, hashtags, punctuation, and numbers, leaving only meaningful words. The sentiment labels (positive, neutral, negative) are then encoded into numerical values using LabelEncoder so they can be used by the machine learning model. The cleaned dataset is split into training and testing sets, with 80% used for training and 20% for testing. A pipeline is created that first applies a TF-IDF vectorizer to convert text into numerical feature vectors based on word importance, and then trains a Logistic Regression classifier to predict sentiment. The model is trained on the training data and then used to predict sentiments for the test set. Model performance is evaluated using accuracy score, a detailed classification report showing precision, recall, and F1-score for each sentiment class, and a confusion matrix visualized with Seaborn to display correct and incorrect predictions. Additionally, the code includes visualizations to show sentiment distribution in the dataset, helping to understand data balance. Overall, the script combines preprocessing, model training, prediction, and evaluation in one workflow, making it suitable for an internship task that requires implementing sentiment analysis with NLP techniques.
