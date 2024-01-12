# What Preoccupies The Minds of the Americans?: Sentiment Analysis, USA and Canada (2014-2023)

## Introduction
Opinion mining is another name for sentiment analysis. It is a natural language processing (NLP) that focuses on determining  the sentiment or emotion  expressed in a piece of tech. 
The  goal is to unravel the subjective idea in the text and then categorize it into different class sentiments. For example, sentiment categorizations are often themed as positive, negative, or neutral.  By sentiment analysis, what goes on consistently in the background of the mind of a statement author could identified. 

## Objective 
The general objective of this project is to understand  what takes centre stage in the minds of Americans, particularly the people of the US and Canada.  The importance of this  is that it produces understanding  and insights into how people's, for example, customer's, emotions  could be managed  to the organization's advantage using tools such  as social media campaigns and reputation management. 

## Data Source and Collection
The dataset for this analysis is composed of sentiment, and text data, comprised of different countries, from the year 2014 to 2013.  
The  original data was sourced from, [see here.](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset)   The dataset  records  emotions, trends, and interactions across various social media platforms. The dataset is user-generated; it provides a snapshot of user-generated content, encompassing text, timestamps, hashtags, countries, likes, and retweets. Each entry  presents  unique stories—moments of surprise, excitement, admiration, thrill, contentment, and more—shared by individuals worldwide.

## Data Analysis 
[The original dataset](https://github.com/Gbenga-Akinyemi/American-Sentiments.2014-2023/blob/main/sentimentdataset.csv) was filtered to focus on the US and Canada-specific data. 

### Data Filtering: 
A sub-dataset comprising US and Canada-only sentiment data was created out of the broad data set. [See it here.](https://github.com/Gbenga-Akinyemi/American-Sentiments.2014-2023/blob/main/sentiment.US.Canada.csv). The following [Python code with dedicated libraries was employed to perform the filtering](https://github.com/Gbenga-Akinyemi/American-Sentiments.2014-2023/blob/main/Data_filtering.code.txt). 

### Average Sentiment by County:
![average_sentiment_by_country](https://github.com/Gbenga-Akinyemi/American-Sentiments.2014-2023/assets/102978818/bebcd246-db6a-4df8-afde-cf9e0cf9cd5d) 

### Average Sentiment by Platforms :
![average_sentiment_by_platform](https://github.com/Gbenga-Akinyemi/American-Sentiments.2014-2023/assets/102978818/86335b2b-d8fa-4edf-bfa0-a9c9e55e1bdd) 

### Top Words by Country : USA: 
![USA_top_words](https://github.com/Gbenga-Akinyemi/American-Sentiments.2014-2023/assets/102978818/dea1f423-6f36-41c1-964d-c118a6a5977b)

### Top Words by Country: Canada: 

![Canada_top_words](https://github.com/Gbenga-Akinyemi/American-Sentiments.2014-2023/assets/102978818/f6e3eac5-61e7-42c4-b93f-d5c99cd7451c) 

## Conclusion:
This  analysis buttresses the fact that the preoccupation of the US for the period under analysis was 'new'. It appeared that Americans were more concerned about how to move to achieve a new state of phase. That is, between 2014 and 2023, America was concerned more about achieving the 'next stage of things'. It could underscore the desire to get new material things such as 'new houses', and 'new cars'. It could also indicate a new state of personal affairs such as a 'new job',' new wife', etc. While Canada during the period of review  cared more about their lives and survival. This could imply a parallel between the Canadian  healthcare system and the people

## References:
1. NLP( Natural Language Processing) libraries of Python were mainly  employed to work out this analysis [The general codes for the analysis iterations could be found here.](https://github.com/Gbenga-Akinyemi/American-Sentiments.2014-2023/blob/main/General.Codes.for.analysis.txt)
2. [Credits: data ](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset)





