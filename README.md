# Banking Intent Classification with NLP

**This project was developed as part of my Machine Learning and NLP training. It serves as a practical application of text classification concepts and model evaluation.**

This project classifies customer queries for telephone banking using Machine Learning.

## Features
- **Dataset:** `bankv3.csv` (Customer queries and labels)
- **Model:** Random Forest Classifier
- **Techniques:** Natural Language Processing (NLP), CountVectorizer, Stopwords removal.

## Requirements
- Python 3.x
- Pandas
- Scikit-learn

## How it works
The model cleans the text by removing common Turkish stopwords, converts text into numerical vectors using `CountVectorizer`, and predicts the intent using a Random Forest algorithm.
