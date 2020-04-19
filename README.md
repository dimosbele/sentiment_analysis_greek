# sentiment_analysis_greek
A Hybrid Method for Sentiment Analysis of Election Related Greek Tweets

Political sentiment analysis using social media content has recently attracted significant interest. This project focuses on analyzing tweets in Greek regarding the recent European Elections (2019). A hybrid method that combines Greek lexicons and classification methods is developed. A probabilistic classification model, that predicts the sentiment of tweets, is combined with hashtag-based filtering. Based on the predictions, an analysis is implemented, that shows how the public sentiment was affected by specific events during the pre-election period. Check the correpsonding paper here https://ieeexplore.ieee.org/document/8908289 .

## Folder analysis

1) modeling - The folder contains the notebook in which the classifier model is created based on the data/df_final.pkl file /n
1.1. modeling.ipynb - Creating the model /n
1.2. /model - The created model (clf.sav)
1.3. /data - The trainset & testset (df_final.pkl)

2) gather_tweets - 
2.1 gather_tweets.ipynb - 
2.2 /data - the dataset with the gathered tweets (tweets.pkl)

3) preprocess_tweets - 
3.1. fix_tweets.ipynb - 
3.2. tweets_syntax.ipynb - 
3.3. lexiconsTofeatures.ipynb - 

4) predictions - 
4.1. predictions.ipynb - 

5) lexicons -
5.1. fix_lexicons.ipynb
5.2. GrAFS_expanded.csv
5.3. KBL.tsv
5.4. greek_sentiment_lexicon.xlsx
5.6 /fixed_lexicons - the 3 above lexicons after preprocessing


