# sentiment_analysis_greek
A Hybrid Method for Sentiment Analysis of Election Related Greek Tweets

Political sentiment analysis using social media content has recently attracted significant interest. This project focuses on analyzing tweets in Greek regarding the recent European Elections (2019). A hybrid method that combines Greek lexicons and classification methods is developed. A probabilistic classification model, that predicts the sentiment of tweets, is combined with hashtag-based filtering. Based on the predictions, an analysis is implemented, that shows how the public sentiment was affected by specific events during the pre-election period. Check the correpsonding paper here https://ieeexplore.ieee.org/document/8908289 .

## - Folders description

1) modeling - The folder contains the notebook in which the classifier model is created based on the data/df_final.pkl file <br>
1.1. modeling.ipynb - Creating the model <br>
1.2. /model - The created model (clf.sav) <br>
1.3. /data - The trainset & testset (df_final.pkl)<br>

2) gather_tweets - The folder contains the notebook with which we gather new tweets from twitter via the official API<br>
2.1 gather_tweets.ipynb - Gathering tweets based on specific hashtags <br>
2.2 /data - the dataset with the gathered tweets (tweets.pkl)<br>

3) preprocess_tweets - The folder contains the notebook with which the gathered tweets are being preprocessed<br>
3.1. fix_tweets.ipynb - The first step of the tweets preprocessing procedure<br>
3.2. tweets_syntax.ipynb - The second step of the tweets preprocessing procedure<br>
3.3. lexiconsTofeatures.ipynb - The third step of the tweets preprocessing procedure<br>

4) predictions - The folder contains the notebook with which we match each tweet to a sentiment (neutral, positive, negative)<br>
4.1. predictions.ipynb - Making predictions regarding the sentiment of each tweet based on the classifier & Creating an analysis and visualization<br>

5) lexicons - The folder contains the greek lexicons and the preprocessing procedure<br>
5.1. fix_lexicons.ipynb - Preprocessing the 3 initial lexicons <br>
5.2. GrAFS_expanded.csv <br>
5.3. KBL.tsv <br>
5.4. greek_sentiment_lexicon.xlsx <br>
5.6 /fixed_lexicons - The 3 above lexicons after preprocessing <br>


Dimosthenis Beleveslis <br>
dimbele4@gmail.com
