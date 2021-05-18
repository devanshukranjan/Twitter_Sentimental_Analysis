# Twitter_Sentimental_Analysis
SOCIAL MEDIA SENTIMENTAL ANALYSIS USING TWITTER DATASET
Twitter boasts 330million monthly active users, which allows business to reach a broad audience and connect with customers without intermediaries. On the downside, there is so much information that it is hard for brands to quickly detect negative social mentions that could harm their business.
That’s why sentiment analysis, which involves monitoring emotions in conversations on social media platforms, has become a key strategy in social media marketing.
Listening to how customers feel on Twitter allows companies to understand their audience, keep on top of what’s being said about their brand, and their competitors, and discover new trends in their industries.

Methodology is use of machine learning and data analysis. 

Langauge used is Python.

Tool used is Jupyter Notebook.

# Imported libraries

from tweepy import OAuthHandler

from tweepy import Cursor

from tweepy import API

import pandas as pd

import re

from textblob import TextBlob

from wordcloud import WordCloud

import matplotlib.pyplot as plt

plt.style.use('fivethirtyeight')
