This repo contains a notebook for builing a recommendation system using Pyspark. It also  contains code for processing big data using Pyspark.

# Data
Anime Recommendations dataset is used in this project. The dataset contains two csv files, namely anime.csv and rating.csv. This data set contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings. 
 
File Description: 
Anime.csv 
•	anime_id - myanimelist.net's unique id identifying an anime. 
•	name - full name of anime. 
•	genre - comma separated list of genres for this anime. 
•	type - movie, TV, OVA, etc. 
•	episodes - how many episodes in this show. (1 if movie). 
•	rating - average rating out of 10 for this anime. 
•	members - number of community members that are in this anime's "group". 
 
Rating.csv 
•	user_id - non identifiable randomly generated user id. 


# Algorithm

The Alternating Least Squares (ALS) matrix factorization recommender algorithm was implemented from PySPark machine learning suite. 

