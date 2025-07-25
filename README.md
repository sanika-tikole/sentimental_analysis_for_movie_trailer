# YouTube Comments Sentiment Analysis
# Project Overview
*This project performs sentiment analysis on YouTube comments for a movie trailer. It processes all comments from an Excel file, calculates sentiment scores using:

*VADER (NLTK) → For numeric sentiment scoring.

*Hugging Face Transformers (distilbert-base-uncased-finetuned-sst-2-english) → For sentiment classification (Positive/Negative/Neutral).

The script also:

*Extracts positive and negative words.

*Computes average sentiment scores for comments.

*Counts neutral comments.

*Generates word clouds for visualizing frequently used positive and negative words.

# Features
*Reads comments from an Excel file (Datafile.xlsx).

*Preprocessing: Removes stopwords for cleaner analysis.

*Sentiment scoring:

*Sentence-level compound sentiment score using VADER.

*Label classification (POSITIVE, NEGATIVE, NEUTRAL) using a Transformers model.

*Word-level analysis: Extracts positive and negative words from comments.

*Aggregated Metrics:

*Average positive and negative sentiment scores.

*Count of neutral comments.

*Final combined sentiment score.

*Visualization:

*Word clouds for positive and negative words.

