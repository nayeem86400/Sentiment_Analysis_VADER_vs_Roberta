# Sentiment_Analysis_VADER_vs_Roberta
A comparison study between NLTKs VADER Sentiment Scoring and Roberta Pre-trained Model


# VADER Seniment Scoring

using NLTK's `SentimentIntensityAnalyzer` to get the neg/neu/pos scores of the text.

- This uses a "bag of words" approach:
    1. Stop words are removed
    2. each word is scored and combined to a total score.
 
# Roberta Pre-trained Model

- model trained on a large corpus of data.
- Transformer model accounts for the words but also the context related to other words.
