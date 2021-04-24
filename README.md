# youtube_sentiment_analysis
* Sentiment analysis is basically concerned with analysis of emotions and opinions from text.  * Since social media introduced, Human being used the media to express their needs, preferences and emotions. And growth in social networks such as Twitter, Facebook ,youtube and others, has gathered a large amount of information on user preferences.
# problem
Analyze people's comments on Doland Trump's speech from YouTube to find out what people's opinions are positive, negative, or neutral, and then build a future business model to predict sentiment analysis.
![Doland Trump's speech](https://www.youtube.com/watch?v=Qsvy10D5rtc)

# Solution

use Natural Language Processing (nlp) and computational techniques to automate the extraction or classification
of sentiment from typically unstructured text

# Approaches to sentiment analysis are of three types

1-machine learrning
-naive base
-svm
-deep learrning

It depends on the presence of data and it has a result(feather,lable)

2-use lexicons 
are a group of words, each word for which the analysis has its  whether positive or negative
The classification is in the form of items or numerical numbers.

3-hybrid solutions(use lexicons and machine learrning)

# in this case we use hybrid solutions
Combining  advantages  for the two approach:
ml :High accuracy
lexicons :Lack of sentiment analysis experts and time-lapse in case comments abound

# Solve the project in two steps

# 1 step
Collecting data from YouTube
# Requirements
--chrome Browser version 81
--chromedriver.exe version 81


# Libraries Used
Libraries Explained in the code
- pandas 
- time
- selenium 
file name : get_comments_yotube
# 2 step
create lableing and model And calculate accuracy
file name : comments_sentiment_analysis
# Libraries Used
Libraries Explained in the code
- pandas 
- matplotlib.pyplot as plt
- textblob import TextBlob 
- wordcloud 
- nltk
- nltk.corpus (stopwords)
- string
- sklearn.feature_extraction.text(CountVectorizer,TfidfTransformer)
- naive_bayes (MultinomialNB)
- sklearn.metrics (confusion_matrix,accuracy_score,classification_report)
- seaborn 
