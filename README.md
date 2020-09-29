# Apple_twitter_data_Sentiment_Analysis
Sentiment Analysis using data collected from twitter.

This projects start with importing our data, processing it to remove un-neccesary columns, missing data, cleaning the text and much more.

Using RegexpTokenizer from nltk, the text was tokenized and some visualizations were made to show the general information about the data.

Then using TfidfVectorizer from sklearn.feature_extraction.text, the values in the dataframe were converted into weighted arguements by calculating word frequency scores that try to highlight words that are more interesting.

Afterwards, fitting a TruncatedSVD from sklearn.decomposition with two labels, a 2D Visual of Word Frequencies was plotted to observe the frequencies of negative and positive sentiment.

We fitted multiple models to achieve our objective and the best model was selected after getting the evaluation metrics. 

After getting the predictions regarding the sentiment, a confusion matrix was plotted. Using the same predictions, the importance of words with both negative and positive sentiment were analysed and the first 20 words were plotted for both labels
