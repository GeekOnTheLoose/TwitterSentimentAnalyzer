# TwitterSentimentAnalyzer
Aim of this project is to analyzes a list of tweets about a topic you feed to the python script and displays a list of tweets with their sentiments 

**Introduction:**

Sentiment Analysis, also called **opinion mining** or **emotion AI**, is the process of determining whether a piece of writing is positive, negative, or neutral. A common use case for this technology is to discover how people feel about a particular topic. Sentiment analysis is widely applied to reviews and social media for a variety of applications.

Sentiment analysis can be performed in many different ways. Many brands and marketers use keyword-based tools that classify data (i.e. social, news, review, blog, etc.) as positive/negative/neutral.

Automated sentiment tagging is usually achieved through word lists. For example, mentions of ‘hate’, 'crime' would be tagged negatively.

There can be **two approaches** to sentiment analysis.

**1. Lexicon-based methods**

**2. Machine Learning-based methods.**

**In this problem, we will be using a Lexicon-based method**

Lexicon based methods define a list of positive and negative words, with a valence — (eg ‘nice’: +2, ‘good’: +1, ‘terrible’: -1.5 etc). The algorithm looks up a text to find all known words. It then combines their individual results by summing or averaging. Some extensions can check some grammatical rules, like negation or sentiment modifier (like the word “but”, which weights sentiment values in text differently, to emphasize the end of text).

Let’s build the analyzer now.

**Twitter API**

Before we start coding, we need to register for the Twitter API https://apps.twitter.com/. Here we need to register an app to generate various keys associated with our API. The Twitter API can be used to perform many actions like create and search.

Now after creating the app we can start coding.

We need to install two **packages**:

**pip install tweepy**

This package will be used for handling the Twitter API.

**pip install textblob**

This package will be used for the sentiment analysis.**

**Note:** If your're using **Anaconda distribution** then refer the links below to install:

**textblob: https://anaconda.org/conda-forge/textblob**

**tweepy: https://anaconda.org/conda-forge/tweepy**
