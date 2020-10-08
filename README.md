# Yelp-Data

# Overview

The work is aimed at using an API to get data and then exploring the data. The Yelp API will be used to get using the Business Search endpoint and then explore the data obtained.

## Goals
- The first goal is to learn how to use the Yelp API to get data, store it and use the data for analysis.
- The second goal is use the data obtained, that is, Italian Restaurants in New York City data to analyse ratings and reviews. We evaluate if ratings only is a good way to assess restaurants or a combination of ratings and reviews.

## Motivation and Background
This project is interesting because you learn how to use an API to get information and then use the data to do meaningful analysis. 

Everyday hundreds of people tour New York. According to Wikipedia, with an annual estimate of 38 million visitors visit the Central Park alone. That is only mention on of the many tourist atrractions in New York. One of the things people do when they go to a new place is look for places to eat. Yelp is a useful tool for finding restaurants and corresponding reviews.  

This study will be useful for anyone wanting to use the Yelp API and then analyze the ratings and reviews count. This study is also useful for a tour company which wants to use the Yelp ratings and reviews so as to get the best restaurants for its customers.

Other people have done work to analyze reviews from Yelp. There are tutorials showing how to analyze sentiment comments, for example [Python Sentiment Analysis](https://www.youtube.com/watch?v=0j3l5GciFIo). Other tutorials on how to webscrape using Yelp API, for example [Webscraping using Requests](https://www.youtube.com/watch?v=vgHwPPRM5JE) 

## Table of Contents
[Code]
[Technical Report]

## Software Requirements

  **Libraries needed for Yelp API** Requests, Numpy, Pandas, JSON, Configparser
  
  **Libraries needed for data analysis** Pandas, Numpy, Matplotlib 

## Data

The data is obtained using the [Yelp API](https://www.yelp.com/developers/documentation/v3). The data is on Italian restaurants in New York City. The data has 210 rows and 16 columns.

The Yelp API requires authentication to use its API. To obtain the authentication one has to open an account with Yelp. For the Business Search Endpoint the data has a limit of 50, if no limit is set it defaults to 20 businesses. You can get a maximum of 1000. 

The data is saved in this repository.

## Resources:
- [Wikipedia](https://en.wikipedia.org/wiki/Central_Park)
- Kazil J. and Jarmul K, Data Wrangling with Python, Tips and Tools to Make Your Life Easier
- [Yelp](https://www.yelp.com/developers/documentation/v3)
- [Webscraping with Requests]((https://www.youtube.com/watch?v=vgHwPPRM5JE)
- [Config files](https://www.youtube.com/watch?v=Gdw0-QGq-z0)
