# toxic-comments-classification

Problem Statement:
  
The task is to analyze a dataset of user comments and identify which ones are toxic. Each comment in the dataset comes with various features such as toxicity scores, additional toxicity types, identity attributes, and user feedback features. The challenge involves cleaning and exploring the data to understand the distribution of these features and the most common words in different types of comments.The cleaned data is then used to train several machine learning models, including Stochastic Gradient Descent (SGD) Regressor and Decision Tree Regressor. The performance of these models is evaluated by calculating the mean squared error (MSE) on the training and validation sets.The text data is then transformed into two different formats: Bag of Words (BoW) and Term Frequency - Inverse Document Frequency (TF-IDF). The same models are trained on the transformed data, and their performance is evaluated.Finally, the data is prepared for training a Long Short-Term Memory (LSTM) model. The LSTM model is trained on the transformed data, and the best model weights are saved. The goal is to find the best model for classifying toxic comments based on the lowest MSE on both the training and validation sets.

Dataset Description:
  
The dataset for this project consists of user comments alongside a variety of associated features. These comments serve as the main text input, while the 'target' feature provides a toxicity score ranging from 0 to 1, with higher values indicating increased toxicity levels. Additionally, the dataset includes toxicity subtype features such as severe_toxicity, obscene, identity_attack, insult, and threat, each offering more specific insights into the type of toxicity present within the comment. Identity attributes are also included, indicating whether the comment mentions various identities such as gender, sexual orientation, religion, race/ethnicity, disability, or mental illness. Finally, user feedback features encompass counts of different reactions (funny, wow, sad, likes, disagree) received by the comment, providing further context for understanding user engagement and sentiment. Overall, this dataset facilitates in-depth analysis and prediction of toxicity levels in user comments, as well as insights into the specific types of toxicity, mentioned identities, and user reactions elicited by the comments.

Dataset link:-https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data
