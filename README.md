# Tales from the Crypto

# RESULTS 

## NER is not RENDERED WELL on GITHUB, so here is the screenshot
---
![BITCOIN NER](Images/BitCoinNER.png)

---

![ETHEREUM NER](Images/EthereumNER.png)
---

![Stock Sentiment](Images/sentimental.jpeg)

## Background

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

This project will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. We will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

We will accomplish the following tasks:

1. [Sentiment Analysis](#Sentiment-Analysis)
2. [Natural Language Processing](#Natural-Language-Processing)
3. [Named Entity Recognition](#Named-Entity-Recognition)

- - -


#### Sentiment Analysis

We use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

We use descriptive statistics to answer the following questions:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?

#### Natural Language Processing

In this section, we will use NLTK and Python to tokenize the text for each coin. Be sure to:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Next, we look at the ngrams and word frequency for each coin.

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

Finally, we generate word clouds for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/btc-word-cloud.png)

![eth-word-cloud.png](Images/eth-word-cloud.png)



#### Named Entity Recognition

In this section, we will build a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner.png](Images/btc-ner.png)

![eth-ner.png](Images/eth-ner.png)

- - -

### Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)

- - -

### Hints and Considerations

The free developer version of the News API limits the total monthly requests, so be careful not to exceed the free limits.

- - -

