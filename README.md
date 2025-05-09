## Overview
This notebook performs sentiment analysis on a dataset of social media posts. The goal is to classify each post as **Positive**, **Negative**, or **Neutral** based on its textual content.

## Dataset
- **Source**: Uploaded CSV file (`sentimentdataset.csv`)
- **Entries**: 732 social media posts
- **Columns**:
  - `Text`: Main content of the post
  - `Sentiment`: Label (Positive, Negative, Neutral)
  - `Timestamp`, `User`, `Platform`, `Hashtags`, `Retweets`, `Likes`, `Country`, `Year`, `Month`, `Day`, `Hour`: Additional metadata

## Project Workflow
1. Define the Problem
   - Objective: Build a model to predict sentiment from post text.
   - Type: Multi-class classification

2. Data Collection & Preparation
   - Import all the libraries
   - Load and explore dataset
   - Drop irrelevant columns (e.g., unnamed index columns)
   - Handle missing values if any
3. Text Preprocessing
   - Clean and Normalize text(Lowercasing, removing, punctuation, etc)
   - Remove all the Non-Informative Columns from our model
   - Using Lemma and Stop Words
   - Organize the Columns by order
   - Tokenization and vectorization 
  
