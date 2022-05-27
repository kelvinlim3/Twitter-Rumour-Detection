# Rumour Detection and Analysis on Twitter
Final project for Natural Language Processing (COMP90042). Given a dataset of Twitter threads with their associated rumour label, we aim to investigate methods to classify the source tweet of a Twitter thread as rumour or non-rumour. To this end, we benchmarked various feature engineering and inference techniques.

<br/><b>Feature Engineering:</b>
- User-specific Attributes
- Sentiment Score
- Most Frequent Tokens
- BERT Tokens (<a href="https://github.com/VinAIResearch/BERTweet">Original Code</a>)

<b>Inference:</b>
- Logistic Regression
- Neural Networks
- ELMo
- BERT

### Dependencies
This program was developed using:
1. Python 3.7.13
2. Tweepy 3.10.0
3. NLTK 3.2.5
4. PyTorch 1.11.0


### How to Run the Code
The main file is 'Final\BERTweet.ipynb'. Move it to the same directory as the file in 'Data' and run the notebook sequentially, following the instructions.
Additonally, 'Final\test_predictions_32.csv' is the final prediction output used for the Kaggle competition (<a href="https://www.kaggle.com/competitions/rumour-detection-and-analysis-on-twitter">link</a>) where the predictions were ranked 11th. 'Final\Twitter Rumour Detection.pdf' is a thorough report on our methodology and findings.