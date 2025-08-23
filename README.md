# Twitter Sentiment Analysis for Indian Elections

This project focuses on analyzing tweets related to the Indian Elections using NLP techniques. It involves data collection, preprocessing, sentiment labeling, exploratory analysis, word embeddings, and deep learning models for sentiment prediction.

## Project Structure

The repository contains five Jupyter notebooks covering the end-to-end workflow:

1. **Portfolio Notebook** – Overview of the project.
2. **Election\_Datascrape** – Fetching tweets using the Twitter API (`tweepy`).
3. **Data\_Labeling** – Cleaning tweets, labeling sentiment (positive/negative), and resampling the dataset.
4. **Exploratory Data Analysis** – Visualizing and understanding dataset trends.
5. **Glove & Bidirectional RNN** – Creating word embeddings with GloVe, building and fine-tuning a BiRNN model.
6. **Tweet\_Prediction** – Making predictions using the trained model.

### Data & Models

* **data.7z** – Contains raw and processed datasets (`Election.csv` is the final dataset used).
* **SavedModel.7z** – Contains the trained GloVe model weights.

## Contributions

* Generated and combined tweet datasets across different months.
* Cleaned, labeled, and resampled the dataset.
* Conducted exploratory data analysis (EDA).
* Created GloVe word embeddings and built a Bidirectional RNN.
* Fine-tuned the model architecture and hyperparameters for improved performance.

## References

* [Tweepy Documentation](http://docs.tweepy.org/en/v3.5.0/)
* [Another Twitter Sentiment Analysis](https://towardsdatascience.com/another-twitter-sentiment-analysis-bb5b01ebad90)
* [Text Data Cleaning in Python](https://www.analyticsvidhya.com/blog/2015/06/quick-guide-text-data-cleaning-python/)
* [Dealing with Imbalanced Classes](https://machinelearningmastery.com/tactics-to-combat-imbalanced-classes-in-your-machine-learning-dataset/)
* [Wordcloud in Python](https://www.datacamp.com/community/tutorials/wordcloud-python)
* [Stanford GloVe](https://github.com/stanfordnlp/GloVe)

## License

[MIT License](https://github.com/abhishek291994/Twitter-Sentiment-Analysis-for-Indian-Elections/blob/master/Liscence.txt)

---
