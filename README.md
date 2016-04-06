# SWE546_Assignment4

MovieLens Recommendation System

http://grouplens.org/datasets/movielens/

Using the MovieLens 1M dataset, and using only the rankings, implement a recommendation sytem using SGD.


import pandas as pd

rnames = ['user_id', 'movie_id', 'rating', 'timestamp']
ratings = pd.read_table('data/ml-1m/ratings.dat', sep='::', header=None, names=rnames)

The output of your program must be the highest estimated rankings for the first 10 movies of the first 20 users






