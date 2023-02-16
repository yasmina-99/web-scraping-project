# web scraping project
 
## Overview
This repository is a solution created to obtain information about coffee places for different cities using Web Scraping with Python programming language. YellowPages widely famous webpage was used for this purpose. <a href="https://www.yellowpages.com/" target="_blank">Google</a>


![alt text](https://github.com/yasmina-99/web-scraping-project/blob/main/selenium_4_logo.png?raw=true)


This scraping project allows the posssibility to scrape data from random locations all around the world every time. Therefore the code is reusable and interactive. First the head of the webpage is explored. Then, using browser automation, it was possible to integrate Selenium with BeatifulSoup to navigate through the different establishments and get data from each of the pages. In conclusion, it's an exploratory idea to think creatively about automation.

## `NLP` Natural Language Processing `Sentiment` Analysis using `nltk` library 

The Natural Language Toolkit (NLTK) library is an open-source library of Python. It was used to conduct a sentiment analysis of the comments of users. This allows to analyse human language data and to draw conclusions from the different reviews. To do so, different packages need to be installed first

``` 
pip install nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('maxent_ne_chunker')
nltk.download('words')
nltk.downloader.download('vader_lexicon')
```

Stops words like rticles, prepositions, pronouns, conjunctions, punctuations are filtered out before doing the NLP analysis. To show a little example of how the model is actually working:

```
> from nltk.classify import NaiveBayesClassifier 
> from nltk.corpus import subjectivity (<br>)
> from nltk.sentiment import SentimentAnalyzer (<br>)
> from nltk.sentiment.vader import SentimentIntensityAnalyzer (<br>)
> from tqdm.notebook import tqdm (<br>)
> sid = SentimentIntensityAnalyzer() (<br>)
> sentiment = sid.polarity_scores("This is the worst thing ever") (<br>)
> print(sentiment)
```


## Branches
All the files are available on the main branch 

## Authors 

The project was designed and optimized by Yasmina Rocio 
You can check out my professional profile on Linkedin here: <a href="https://www.linkedin.com/in/yasmina-rocio-luzardo/" target="_blank">Google</a>

## Citations 

*Bird, Steven, Edward Loper and Ewan Klein (2009), Natural Language Processing with Python. O'Reilly Media Inc.*

*Richardson, L. (2007). Beautiful soup documentation. April.*

![alt text](https://github.com/yasmina-99/web-scraping-project/blob/main/Beautiful-Soup-4-Pot-1.svg?raw=true)

