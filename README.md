# Movie Recommender System

From here Download the dataset(228 MB)- https://www.kaggle.com/rounakbanik/the-movies-dataset

This is a Content-Based Recommender System. Here filtering is based on description of the film, and suggestions are given using user's preferred choices. Algorithm try to recommend products which are similar to the ones that a user has liked in the past.

Criterion Used-  IMDB's Weighted Rating (WR) = (v/(v+m)*R) + (m/(v+m)*C)

where ,

-v is number of votes for the movie.
-m is the minimum votes required to be listed in the chart.
-R is the average rating of the movie.
-C is the mean vote accross the whole report.



