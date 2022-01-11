# Analyzing Twitter Users' 2020 Reflections using NLP


In the [Jupyter Notebook](https://github.com/jess-data/Twitter-2020-Sentiment-Analysis/blob/master/Twitter%20Sentiment%20Analysis%20Project.ipynb), you will leearn how I carried out the following steps for the project:

1. Import Libraries
2. Tweets Mining
3. Data Cleaning
4. Location Geocoding
5. Tweets Processing
6. Data Exploration
7. Sentiment Analysis



## Word Cloud Generation
To get the most common words used to describe 2020, I made use of the POS-tag (Parts of Speech tagging) module in the NLTK library. Using the WordCloud library, one can generate a Word Cloud based on word frequency and superimpose these words on any image. In this case, I used the Twitter logo and Matplotlib to display the image. The Word Cloud shows the words with higher frequency in bigger text size while the "not-so" common words are in smaller text sizes.

![alt text](https://github.com/jess-data/Twitter-2020-Sentiment-Analysis/blob/master/wordcloud.png)

## Visulizing Most Common Words
The Plot below was genrated using Plotly Library for Python.

![alt text](https://github.com/jess-data/Twitter-2020-Sentiment-Analysis/blob/master/Twitter%20analytics%20pic.png)

## Sentiment Analysis
For this analysis, I went with TextBlob. Text Blob analyzes sentences by giving each tweet a Subjectivity and Polarity score. 
Based on the Polarity scores, one can define which tweets were Positive, Negative, or Neutral. A Polarity score of < 0 is Negative, 0 is Neutral while > 0 is Positive. I used the "apply" method on the "Polarity" column in my data frame to return the respective Sentiment Category. The distribution of the Sentiment categories is shown below.

![alt text](https://github.com/jess-data/Twitter-2020-Sentiment-Analysis/blob/master/Distribution%20of%20Sentiments%20Results.png)



