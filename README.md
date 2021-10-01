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

###Entities, linkages, timeframe and algorithmic biases

With Reddit API, the information like the contents for each user's posts are avaliable, such as images, text, upvotes, downvotes, comments and the information about user himself.
With R/WallstreetBets API, the focus of information is the number of comments, sentiment, sentiment score, ticker. There are more than 50 instances of an entity, such as “url”, “upvote_ratio” etc, are avaliable and can all be retrieved with Reddit API. For R/WallstreetBets AP, there are 4 entitles that can be retrieved via tickers. We are aiming to gather the date for the whole set, which is the posts data that are available for the entire day. 
In the Reddit API, the contents of the post like images, upvotes/downvotes and comments forms the posts and the contents of posts linked to the its author/user within the community and to the external entities. By using R/WallstreetBets API, the sentiment and number of comments per ticker (stock) is stored and a sentiment score is retrieved.
The sentiment of the post can be linked via the ticker entity that links with corresponding stock. 
The comment section and awards might affect the display of data for Reddit API. All the raw data can be transformed for both Reddit API and R/WallstreetBets API. 

###Identifiers (E.g. number of comments, sentiment, ticker etc.)
For Reddit API, the identifiers we are interested to gather are permalink, title, the content of the post, author, upvotes and upvote ration, image, total awards received and flair, number of comments and the datetime. 
For R/WallstreetBets API is the sentiment score of the post, the linked stock name,

Reddit API can collect the data for top today for example, which starts from the current instance and cover the whole day. R/WallstreetBets API can collect the information from 15 minutes before and it is updated every 15 minutes.

###Sampling, construct measurement and data structure (5%)
Both Reddit API and R/WallstreetBets API data will be saved in a csv file for each single day. The constructs of interest be measured with the available data for Reddit API and for the R/WallstreetBets API, the sentiment has a continuous measurement and can be used when combined with other APIs.

###Data inspection per entity (10%)

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
