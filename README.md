# Sentiment Analysis NLP

## Project Overview

This project performs sentiment analysis on text data using Natural Language Processing (NLP) and Machine Learning.

The model classifies text into three sentiment categories:

- Positive
- Negative
- Neutral

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Natural Language Processing (NLP)

## Dataset

The dataset contains 15 sample text reviews with their corresponding sentiment labels.

The dataset includes:

- 5 Positive texts
- 5 Negative texts
- 5 Neutral texts

This is a small sample dataset created for learning and demonstration purposes.

## Data Preprocessing

The text data was cleaned using:

- Conversion of text to lowercase
- Removal of special characters
- Removal of extra spaces

## TF-IDF Vectorization

TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert the cleaned text into numerical features that can be used by the machine learning model.

## Machine Learning Model

A Logistic Regression model was trained to classify the text into:

- Positive
- Negative
- Neutral

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The test set contained only 3 samples, and the resulting accuracy was 0.0.

Because the dataset is very small, these evaluation results are not representative of real-world model performance. The project is intended for learning and demonstration purposes.

## New Text Predictions

The trained model was also tested on new text examples.

Example predictions:

- "I really love this amazing product" → Positive
- "This service is very bad" → Negative
- "The product is okay" → Neutral

## Confusion Matrix

A confusion matrix was created to visualize the classification results for the test data.

## Project Workflow

1. Create the sentiment dataset
2. Check the dataset
3.  Clean the text
4. Convert text into TF-IDF features
5. Split data into training and testing sets
6. Train Logistic Regression model
7. Predict sentiments
8. Evaluate the model
9. Test new text samples
10. Visualize results using a confusion matrix

## Conclusion

This project demonstrates a basic Natural Language Processing workflow using text preprocessing, TF-IDF vectorization, and Logistic Regression for sentiment classification.

The project provides practical experience in applying NLP and machine learning techniques to text data.
