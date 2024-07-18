# Fake-News-Detection (Text Dataset from Kaggle)
This project aims to detect fake news using Logistic Regression. It involves preprocessing text data through stemming and transforming it using TF-IDF Vectorizer.

Dataset

The dataset used for this project can be found on Kaggle.(https://www.kaggle.com/competitions/fake-news/data?select=train.csv)

About the Dataset

The dataset contains the following columns:

id: Unique id for a news article.
title: The title of a news article.
author: Author of the news article.
text: The text of the article; could be incomplete.
label: A label that marks whether the news article is real or fake.
1: Fake News
0: Real News

Project Structure

Importing the Dependencies: Import necessary libraries and packages.

Data Preprocessing: Prepare the dataset for training by handling missing values and performing text preprocessing.

Stemming: Apply stemming to reduce words to their root form (e.g., actor, actress, acting → act).

Splitting the Dataset: Divide the dataset into training and testing sets.

Training the Model: Train a Logistic Regression model on the processed dataset.

Evaluation: Evaluate the model using metrics such as Accuracy Score.

Making a Predictive System: Implement a system to predict if a news article is real or fake.

Evaluation

The model's performance is evaluated using the Accuracy Score metric. The notebook contains code to assess the model's accuracy on the test set.


