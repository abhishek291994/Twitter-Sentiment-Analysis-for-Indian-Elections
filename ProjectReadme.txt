The main folder contains 5 ipython notebooks.
1. portfolio notebook gives the over view of the project.
2. Election_datascapre (code for fetching tweets using the twitter api tweepy)
3. Data_Labeling (code for labeling tweets as positive or negative based on the sentiment score. Resampling procedure for the data)
4. Exploratory Data Analysis
5. Glove model 
6. Bidirectional RNN
7. Tweet_prediction

The data.7z contains all the data files(Election.csv is the final dataset that was used for the analysis)
The SavedModel.7z contains the models weights for Glove model

Contributions:
1. Generated the tweet datasets, combined data from different months.
2. Cleaned the tweets, labeled and resampled the dataset.
3. Performed exploratory data analysis
4. Created word embeddings using Glove. Built a model on top of the embeddings. Fine tuned the model by varing the nodes and architecture of the model. 



References:

1.http://docs.tweepy.org/en/v3.5.0/
2.https://towardsdatascience.com/another-twitter-sentiment-analysis-bb5b01ebad90
3.https://www.analyticsvidhya.com/blog/2015/06/quick-guide-text-data-cleaning-python/
4.https://machinelearningmastery.com/tactics-to-combat-imbalanced-classes-in-your-machine-learning-dataset/
5.https://www.datacamp.com/community/tutorials/wordcloud-python
6.https://github.com/stanfordnlp/GloVe


Liscence:
MIT License https://github.com/abhishek291994/Twitter-Sentiment-Analysis-for-Indian-Elections/blob/master/Liscence.txt
