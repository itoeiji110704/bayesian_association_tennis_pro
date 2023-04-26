![](https://img.shields.io/static/v1?label=python&message=3.6.6&color=blue)
![](https://img.shields.io/static/v1?label=last%20updated&message=december%202018&color=lightgray)

# bayesian_association_tennis_pro

This repo has the notebook that tried to the bayes modeling of latent strength of each men's pro-tennis player using the following kaggle dataset which include a result of men's pro-tennis matches.

Used dataset: https://www.kaggle.com/datasets/gmadevs/atp-matches-dataset

It seems like that each pro-tennis player has their potential strength (latent strength).  
On the other hand, it seems like that sometimes they could perform full potential due to they were good condition, and sometimes they couldn't perform well due to they were not good condition. So we can recognize this as their "uneven performance".  
It can consider that the result of the match is determined by which performance is bigger. (bigger will win).  
It can estimate each player's latent strength and uneven performance using a bayesian modeling.  
  
The analysis is divided into two parts, Part A and Part B.  
In Part A, using information of each player's wins and losses during a target period, tried to estimate the player's latent strength and uneven performance in the period.  
In Part B, extended the analysis of Part A by incorporating the state space modeling, estimated how changed the player's latent strength and uneven performance on time series.  
  
See `bayesian_modeling_pro-tennis_player_strength.ipynb`  
  
This analysis has been republished in detail as part of the following book (Chapter 6).  

<a href="https://www.amazon.co.jp/%E3%81%9F%E3%81%AE%E3%81%97%E3%81%84%E3%83%99%E3%82%A4%E3%82%BA%E3%83%A2%E3%83%87%E3%83%AA%E3%83%B3%E3%82%B02-%E4%BA%8B%E4%BE%8B%E3%81%A7%E6%8B%93%E3%81%8F%E7%A0%94%E7%A9%B6%E3%81%AE%E3%83%95%E3%83%AD%E3%83%B3%E3%83%86%E3%82%A3%E3%82%A2-%E8%B1%8A%E7%94%B0-%E7%A7%80%E6%A8%B9/dp/4762830836">"Exciting Bayes modeling 2: Frontiers of research opened by cases"</a>
