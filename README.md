# Twitter_Sentiment_Analysis-and_Stock_Prediction
#predicting_stock_prices Stock Prediction

This is the code for the Stock Price Prediction challenge for '#Hack2Innovate'. The code uses the [scikit-learn](https://github.com/scikit-learn/scikit-learn) machine learning library to train a support vector regression on a stock price dataset from [Google Finance](https://en.wikipedia.org/wiki/Support_vector_machine) to predict a future price. In this I use scikit-learn to build an ML model, but for the challenge you'll use the [Keras library](https://keras.io/).


There are two scripts. ```demo.py``` is the code ```challenge.py``` is a template for the coding challenge that will complete.

**#Dependencies**
---

* numpy (http://www.numpy.org/)
* tweepy (http://www.tweepy.org)
* csv (https://pypi.python.org/pypi/csv)
* textblob (https://textblob.readthedocs.io/en/dev/)
* keras (https://keras.io)

**#Demo Usage**
---

Once you have your dependencies installed via pip, run the demo script in terminal via

```python demo.py```


**#Challenge**
---

The challenge template in this repo labeled``` challenge.py```. The instructions are:

[Get your Twitter Consumer key, Consumer secret, Access token, Access secret here!](https://apps.twitter.com/)

[To know how to get Twitter access tokens Click Here!](https://developer.twitter.com/en/docs/basics/authentication/overview)

Here i use the Tweepy library to retrieve tweets about a company stock from twitter.

Here i also use the TextBlob library to classify those tweets as either positive or negative given a threshold  that i define.

If the majority of tweets are positive, then the Keras library is use to build a neural network that predicts the next stock price given a dataset of past stock prices that will pull from Google Finance. 

![The Sentimental Graph](https://github.com/vedicnis/Twitter_Sentiment_Analysis-and_Stock_Prediction/blob/master/Figure_1.png)
