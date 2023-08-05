# OIBSIP_2-Email_spam_detection
Email_spam_detection
Overview
This project focuses on Email Spam Detection using Machine Learning techniques. The objective is to develop a model that accurately classifies emails as spam or non-spam (ham). The project was completed as part of my internship at Oasis Infobyte.

Dataset
The dataset provided for this project consists of 5,572 email samples. To train and evaluate the model, I split the dataset into training (80%) and testing (20%) sets. This ensured sufficient data for training and unbiased evaluation.

Data Preprocessing
During data preprocessing, I dropped irrelevant columns ('Unnamed: 2', 'Unnamed: 3', 'Unnamed: 4') from the dataset. These columns were not essential for the classification task. The remaining data was used for further analysis and model training.

Feature Extraction
To convert the textual content of emails into a numerical representation, I utilized the CountVectorizer technique. It transformed the text data into a matrix of token counts, creating a vocabulary of unique words. This allowed encoding emails into numerical feature vectors based on word frequencies.

Machine Learning Algorithms
I experimented with two popular algorithms:

Logistic Regression:

Achieved a training accuracy of 99.76% and testing accuracy of 97.58%
Logistic Regression generalized well to unseen email samples
Support Vector Machine (SVM):

Achieved a training accuracy of 99.59% and testing accuracy of 97.49%
SVM showcased effectiveness in email spam detection
Conclusion
This project successfully demonstrates the implementation of machine learning techniques for Email Spam Detection. The models developed using Logistic Regression and SVM achieved high accuracy in classifying emails. The project showcases the importance of data preprocessing, feature extraction using CountVectorizer, and the performance of different algorithms.

Please feel free to reach out to me for further information or discussions related to this project.

Keywords: Machine Learning, Email Spam Detection, Data Preprocessing, CountVectorizer, Logistic Regression, Support Vector Machine (SVM), Internship, Oasis Infobyte
