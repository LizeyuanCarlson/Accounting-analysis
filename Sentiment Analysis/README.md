# Sentiment Analysis on the MD&A language

This repository is to show how to apply sentiment analysis on the 10 k Management discussion and analysis of one company. 

It treats the management discussion and analysis language as a bag of words.

The sentiment is defined as (# of positive words - # of negative words)/ total words. Research has found that MD&A sentiment is predictive of future returns.

The dictionary used is McDonald Dictionary. 

NLTK library will help do not count positive or negative words because of potential ambiguity or count of 
negated positive words as negative. ex: We are not unhappy with the performance.
