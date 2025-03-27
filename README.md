# Airline Tweet Sentiment Analysis

This repository contains a sentiment analysis model that classifies tweets related to airlines. The model is trained using a logistic regression approach on preprocessed tweet text.

## Project Overview

The main file is **`AIA.ipynb`**, which contains:
- The preprocessing pipeline for cleaning the tweets
- A **Logistic Regression** model for sentiment classification (positive, neutral, negative)
- Evaluation metrics and confusion matrix
- Gradio interface for real-time prediction

## How to Run

1. Download or clone this repository.
2. Open the Jupyter notebook **`AIA.ipynb`**.
3. Follow the instructions in the notebook to train the model and predict sentiment from new tweets.

## Dependencies

To run the notebook, you need the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- scikit-learn
- gradio

Install the dependencies using:
```bash
pip install -r requirements.txt
