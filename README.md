# Sentiment Analysis on Movie Reviews

## Purpose

This project aims to perform sentiment analysis on movie reviews using machine learning techniques. Sentiment analysis involves determining the sentiment expressed in a piece of text, which can be positive, negative, or neutral. By analyzing movie reviews, we can gain insights into audience opinions and preferences regarding different films.

## Functionality

    Data Acquisition:
        The project reads movie review data from a CSV file.

    Text Preprocessing:
        Preprocesses the text data by:
            Removing HTML tags
            Removing emoticons
            Removing non-alphanumeric characters
            Removing stopwords
            Stemming using the Porter stemming algorithm

    Feature Engineering:
        Uses TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text data into numerical features.

    Model Training:
        Trains a logistic regression classifier on the preprocessed data.

    Model Evaluation:
        Evaluates the classifier's performance on a test set.

    Model Persistence:
        Saves the trained model using pickle for future use.

## Machine Learning Models

    The main machine learning model used in this project is logistic regression. Logistic regression is a binary classification algorithm that predicts the probability of a given input belonging to a particular class. In this case, it predicts whether a movie review expresses positive or negative sentiment.

## Techniques Used

    Text Preprocessing:
        Text data is preprocessed using techniques such as:
            Removing HTML tags
            Removing emoticons
            Removing non-alphanumeric characters
            Removing stopwords
            Stemming using the Porter stemming algorithm

    TF-IDF Vectorization:
        TF-IDF is used to convert text data into numerical features while giving importance to terms that are frequent in a document but rare in other documents.

    Logistic Regression:
        Logistic regression is employed as the classification algorithm due to its simplicity and effectiveness in binary classification tasks.

## Results

    After training and evaluating the logistic regression model, the following results were obtained:
        Accuracy on the test set: [Insert accuracy score here]
        Other evaluation metrics (if applicable): [Insert other metrics here]

## Conclusion

Sentiment analysis on movie reviews provides valuable insights into audience sentiments towards different films. By leveraging machine learning techniques such as logistic regression and TF-IDF vectorization, we can automate the process of analyzing large volumes of text data, enabling faster decision-making in the entertainment industry.
