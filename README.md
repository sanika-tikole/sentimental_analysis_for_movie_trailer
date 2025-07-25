# YouTube Comments Sentiment Analysis
# Project Overview
This project performs sentiment analysis on YouTube comments for a movie trailer. It processes all comments from an Excel file, calculates sentiment scores using:

VADER (NLTK) → For numeric sentiment scoring.

Hugging Face Transformers (distilbert-base-uncased-finetuned-sst-2-english) → For sentiment classification (Positive/Negative/Neutral).

The script also:

Extracts positive and negative words.

Computes average sentiment scores for comments.

Counts neutral comments.

Generates word clouds for visualizing frequently used positive and negative words.

# Features
Reads comments from an Excel file (Datafile.xlsx).

Preprocessing: Removes stopwords for cleaner analysis.

Sentiment scoring:

Sentence-level compound sentiment score using VADER.

Label classification (POSITIVE, NEGATIVE, NEUTRAL) using a Transformers model.

Word-level analysis: Extracts positive and negative words from comments.

Aggregated Metrics:

Average positive and negative sentiment scores.

Count of neutral comments.

Final combined sentiment score.

Visualization:

Word clouds for positive and negative words.
# Requirements
Install dependencies:
pip install torch transformers nltk vaderSentiment wordcloud matplotlib openpyxl



# output
Average Positive Score: 0.5456307692307693
Average Negative Score: -0.4715076923076923
Final Sentiment Score: 0.0011403550295857993
Number of Neutral Comments: 35
All Positive Words:      wish like kindness better perfect   bold 😂 happy  great  better Best         feeling happy Happy     supports innocent          kind  pretty good      Iphone😂                    Ok nice Great Please ✋          😂😅 amazing   classy  LOVED  good excited  ok great    😂💀 lol    best  
All Negative Words:    hate jealous Keller😭     misery     dislikes    poison         tears dislike worry  dislikes crazy   ruined   blind hiding dislikes  dislikes unstable   nah    sucks bad BSOD hatred   dislikes bad collapsing bad poisoned  stop  Worst  hate dislikes   dislikes           jump😭  flop        Terrible  nah    lost        worst 
