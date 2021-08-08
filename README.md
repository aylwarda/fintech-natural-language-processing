# fintech-natural-language-processing

This project is part of my Fintech homework, in which I use natural language processing techniques (sentiment analysis, etc.) to determine the prevailing sentiment of Bitcoin and Ethereum which is analaysed against very recent/up-to-date online sources (at the time of creation: Aug 7, '21).

---
## Instructions / Intro

This Project consists of a single Jupyter Notebook (`crypto_sentiment.ipynb`) which runs through the NLP techniques as described above.  
To run through the Notebook, execute it and have a look at the visualisations (e.g. word clouds, named entities) and data produced and draw your own conclusions.  
All the data used in this Notebook is pulled from online sources (News API) which is a departure from other projects/repositories I have recently been involved in.

---
## Natural Language Processing Techniques
This Notebook explores the benefits of using a number of natural language processing techniques (or models) with the primary objective of understanding the prevaling sentiment of the two main crypto platforms/coins in today's markets (Bitcoin and Ethereum).

### Techniques Used

**Sentiment Analysis**  
This explores the sentiment (positive, neutral or negative) of each of the articles (100 for each Coin) and compares the sentiment of Bitcoin against Ethereum and visa versa.  

**Classic Natural Language Processing (NLP)**  
With NLP we explore the breaking down of the many articles into words using a process called tokenisation (in this case the "Natural Language Toolkit (NLTK) library was used) and lemmatisation, distilling the essence of what each article is saying, but also the entire body of news.  Word counts, bigrams, etc. also extracted and then visualised in Word Clouds.

**Named Entity Recognition (NER)**  
With NER we again look at the entire "body of news" and using SpaCy (an amazing library :)) we look at the articles (no punn intended) and sentences from a different angle in that every portion of every sentence is broken down in a number of ways, which makes understanding each article easier. NER seeks to name entities of every sentence linguistically, i.e. Bob is a name (and a noun), ten is a number (and an adjective), Google is an organisation, et cetera.  This is powerful for a number of real-world applications.  Tokenisation is implicit with SpaCy, making the extraction of all entities and easy task.

### Sidenote on [SpaCy](https://spacy.io/)
I had not used SpaCy before this section of the course, and was surprised how amazing it is.  I love linguistics, syntax, grammar; it is my thing! I enjoyed learning about it growing up and I enjoy watching videos on linguistics, accents and how the differences in communication and the use of language has arisen regionally in many countries around the world. My reference point is English, of course.  
Anyway, to cut a long story short, what SpaCy allows in terms of tokenising, lemmatisation and visualisation of language is outstanding; just saying!

---
## Acknowledgements
### Sources
- A "Starter Notebook" was provided by Trinity College as part of course work, which I have built upon.
- Online data source is NewsAPI; learn all about them [here](https://newsapi.org/).
- Natural Language Toolkit Library was used; find more [here](https://www.nltk.org/).
- SpaCy "Industrial-Strength" Natural Language Processing [here](https://spacy.io/) engine with visualisations, et cetera.


