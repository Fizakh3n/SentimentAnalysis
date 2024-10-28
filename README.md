# Sentiment Analysis Web Application

This repository contains a web application built for sentiment analysis using machine learning. The application allows users to input text and receive sentiment classifications (Negative, Neutral, or Positive).

## Project Overview

### Objective
- Developed a sentiment analysis model using a dataset with labels -1 (Negative), 0 (Neutral), and 1 (Positive).
- Preprocessed the text data to remove noise and prepare it for modeling.
- Created a user-friendly web application using Flask, where users can input text and receive sentiment predictions.

### Action
1. **Data Preprocessing**: 
   - Cleaned the text data by converting it to lowercase, removing URLs, and tokenizing.
   - Mapped numerical labels to categorical sentiment labels for user-friendly output.

2. **Model Training**:
   - Trained a machine learning model (XGBoost) on the preprocessed dataset to predict sentiment.

3. **Web Application**:
   - Set up a Flask backend to handle user input and predictions.
   - Designed the frontend using HTML and CSS, incorporating a visually appealing layout.

## Requirements
To run this application, you'll need:
- Python 3.x
- Flask
- scikit-learn
- pandas
- numpy
- nltk
- xgboost

You can install the required packages using:
```bash
pip install -r requirements.txt
