# Effect of r/WallStreetBets on stock prices

## Contributors
Team 2 
members: [Doria Wengting Wang](https://github.com/DoriaWW), [Inge Oostveen](https://github.com/IngeOostveen), [Ralph Delsing](https://github.com/RalphGit21), [Paulus Hovens](https://github.com/pphovens), [Wouter Floors](https://github.com/WouterFloors)

# 1. Documentation

## 1.1. Motivation

### Motivation for data context

r/Wallstreetbets is a community within Reddit that discusses stocks and options and includes roughly 11 million members. WallStreetBets is also known due to some members placing orders (or "bets") on the stock market that include a lot of risk. For some stocks in particular, WSB was found to have a significant effect on the stock price, such as for Gamestop (GME). While some large hedge funds shorted lots of this stock, members of WSB started buying up lots of this stock leading to stock prices to increase, which consequently led to the hedge funds being forced to buy the stocks they shorted, triggering a "short squeeze".
By analyzing the sentiment scores of a stock in a given time period while taking the market cap and volume of the stock into account, the relative influence of the community on stock prices can be assessed. 
With this data, researchers can study the impact of WSB on the stock market. For example: do certain posts or flairs affect certain stocks? Do prices go up or down due to certain comments? 

### Motivation for choice of website/API

The API's used here are the WallStreetBets API and the Reddit API. These data sources are publicly available through the API's and also partly on other platforms such as Github or Kaggle. 
The WSB API allows to easily view the number of comments on each stock discussed on the subreddit daily, while also being able to see the sentiment score. Moreover, the Reddit API on the subreddit gives complementary data that could be useful for research, such as the number of upvotes/downvotes on a post, whether images were used in a post or the number of total awards a post received on the subreddit. By combining these two API's and extracting the data on these once every 24 hours for a number of days, the data could be used for research on the influence of WSB on certain stock prices. 

Small amount of identifiers with a lot of data
Data for every single comment and sentiment placed on r/wallstreetbets
Data on every single stock price and volume


## 1.2 Composition 

Entities, linkages, timeframe and algorithmic biases (5%)

Identifiers (E.g. number of comments, sentiment, ticker etc.)

Sampling, construct measurement and data structure (5%)

Data inspection per entity (10%)

## 1.3 Collection process

Technical extraction plan 

Legal and ethical concerns 

## 1.4 Preprocessing

Preprocessing

Accessibility and structure of final data files

## 1.5 Uses
Users of the data learn about tasks the data set could be used for 

## About

This study is conducted by project group 2 of the [Online Data Collection and Management course](https://github.com/hannesdatta/course-odcm) of the TISEM department of Tilburg University. 
The project is done in the fall 2021 version of the course. The project was part of a team project performed by Marketing Analytics master students. Professor [Hannes Datta](https://github.com/hannesdatta) contributed by providing helpful feedback during project feedback meetings.
