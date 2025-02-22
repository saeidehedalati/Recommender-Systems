
# Recommender Systems 

(source: https://grouplens.org/datasets/movielens/100k/)

Creating a recommendation system for Movies using Lens Data Set.

Data Set Information:

MovieLens data sets were collected by the GroupLens Research Project
at the University of Minnesota. The data was collected through the MovieLens web site (movielens.umn.edu) during the seven-month period from September 19th, 1997 through April 22nd, 1998.
 
This data set consists of:
- 100,000 ratings (1-5) from 943 users on 1682 movies. 
- Each user has rated at least 20 movies. 
- Simple demographic info for the users (age, gender, occupation, zip)

Relevant Paper:

F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets:
History and Context. ACM Transactions on Interactive Intelligent
Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages.
DOI=http://dx.doi.org/10.1145/2827872


### Apply Methods

**Collaborative Filtering (CF)** is one of the two most common types of recommender systems. It produces recommendations based on the knowledge of users’ attitude to items, that is it uses the "wisdom of the crowd" to recommend items. 

CF can be divided into **Memory-Based Collaborative Filtering** and **Model-Based Collaborative filtering**. 

**Memory-based models** are based on similarity between items or users, where here the cosine-similarity is used.
**Model-based CF** is based on matrix factorization where, here singular value decomposition (SVD)is used to factorize the matrix.
