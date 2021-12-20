# Fifa22 Tweets Sentiment Analysis and Classification Models 

## Project Instructions 
Using the Twitter Developer API, we collected tweeter data on the topic FIFA22 over a period of time and saved it in a CSV file.
We then performed text and sentiment analysis using the tweets to 
We also created 4 different classification models, them being : Logistic Regression, Decision Trees, Naive Bayes and CTree
Choose between Association Rules or Clustering.

### Objective:

Since the world of gamers keeps growing and many gamers try out new games that come out every year, we are going to provide them with the best feedback on FIFA 22 which is considered one of the best soccer video game around the world. Every year the gamers judge and draw  a conclusion about the game based on different variables. The objective of the project is to understand and come up with a conclusion about how successful was the game this current year based on different opinions and beliefs. 

### Steps to obtain data:

We will collect the twitter data that mention FIFA22. We will then convert our data to a data frame and filter our data. We will then separate the data into positive and negative. The positive will represent the tweets that are talking well about the game. Our dependent variable is if people think FIFA22 is good or not. The independent variables are education level, religion, gender, age and location. 

We are going to collect data from twitter from the past 7 days about what people think of the FIFA22, if it is better than the previous versions or not, and the characteristics of the people commenting about it, such as age, gender, location and so on. After we collect the data, we will mutate new columns to represent peoples' sentiment as positive and negative, then we will run the regression or other models to analyze the relationship between the dependent and independent variables. 

## Project Contributors 

Georgios Koutsopodiotis (@gkoutso)
 - ST. Thomas University Carnival Cruise Lines School of Science

Carlin Celius (@Cman293)
 - ST. Thomas University Carnival Cruise Lines School of Science

## Libraries Required
The libraries that are required for this project are: 
- library(tidyverse)
- library(jsonlite)
- library(stringr)
- library(tm)
- library(quanteda)
- library(wordcloud)
- library(RColorBrewer)
- library(lubridate)
- library(stringr)
- library(reshape2)
- library(lda)
- library(party)
- library(rpart)
- library(rpart.plot)
- library(caTools)
- library(e1071)
- library(ggplot2)
- library(sentimentr)
- library(httr)
- library(rtweet)
- library(httpuv)
- library(plyr)
- library(tidyr)
- library(tidytext)
- library(twitteR)
- library(purrr)
- library(dplyr)
