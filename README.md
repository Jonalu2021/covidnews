# COVID-19 news on Twitter, a statistical analysis

## Research Questions 
1: What are the most common topics and types of words for identifying fake news about COVID-19 on Twitter?

2: What is the major sentiment in the real and fake news about COVID-19 on Twitter?

## Dataset

### Comprehensive Fake News Diffusion Dataset during COVID-19 Period
https://raw.githubusercontent.com/merry555/FibVID/main/claim_propagation/claim_propagation.csv

0 as COVID True claims ; 1 as COVID Fake claims

The news claims were collected from two fact-checking sites Politifact and Snopes, from January 2020 to December 2020. After that, claim-related tweets and retweets were extracted from Twitter.  

## Sampling 
### Sample 1 for Common topic and words
#### Sampling Method: Extracting 5,000 each for true and fake news claims 
<img src="news1.png" alt="image description" width="500"/>

### Sample 2 for Sentiment analysis
#### Sampling method: Taking a random sample of 30,000 news claims

## Methods
### Machine Learning Algorithms
#### 1. Naive Bayes
- Multinomial 
- Log probability for feature importance
#### 2. Random Forest Classifier
- Bootstrapping
- Gina impurity scores
- Act as a benchmark for Precision Score of Naive Bayes

## Evaulation 
Naive Bayes (NB) Vs Random forest classifier (RF)
Precision score : 76.905%(NB) > 72.152% (RF)

## Discussion
Common words for fake news: “imposter” and “hypocrisies”
<img src="stacked_bar_plot.png" alt="image description" width="500"/>





