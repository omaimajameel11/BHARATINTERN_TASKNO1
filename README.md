# BHARATINTERN_TASKNO1

## SMS CLASSIFIER

This project focuses on building a text classification model to classify SMS messages as either spam or non-spam. We will use data science techniques, including data preprocessing, feature extraction, and machine learning, to achieve this goal.


## Dataset

The dataset used for this project contains SMS messages labeled as either "spam" or "ham" (non-spam). It is stored in the `data/spam.csv` file.


## Dependencies

The project requires the following Python packages:

- pandas
- numpy
- scikit-learn
- nltk
- jupyter
- seaborn

## Implementation

In this implementation:

- We preprocess the text by converting it to lowercase, removing punctuation, tokenizing, removing stopwords, and lemmatizing.
- We extract features using TF-IDF with bigrams.
- We add additional features like text length, number of punctuation marks, digits, and uppercase letters.
- We combine all features into a single feature matrix.
- We train a Logistic Regression model and evaluate its performance.
These features provide a robust foundation for classifying SMS messages as spam or non-spam.
