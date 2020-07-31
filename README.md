# Movie Recommendatio System
Movie Recommendation system using collaborative filtering in Spark and ElasticSearch.  

# Collaborative filtering model
Used MovieLens small dataset, containing movie rating information for 610 users, 9724 movies and 100,000 ratings.  
Trained collaborative filtering model using python in Apache Spark.  
Tuned hyperparater (latent variables k and L2 regularization parameters) using grid search.  
Reached RMSE error rate 0.723 and top 2 recommendation hit rate 86%.  

# Serving on ElasticSearch
Import feature vectors for movies and users into ElasticSearch.  
Given a user, calculate user-movie cosine-similarity and recommend top k highly rated movies. Pull movie info and posters using TMDb API. 
