# movie-recommender-system

What are Recommender Systems?
Recommender systems are an important class of machine learning algorithms that offer “relevant” suggestions to users. Youtube, Amazon, Netflix, all function on recommendation systems where the system recommends you the next video or product based on your past activity (Content-based Filtering) or based on activities and preferences of other users similar to you (Collaborative Filtering). Likewise, Facebook also uses a recommendation system to suggest Facebook users you may know offline.

Recommendation Systems work based on the similarity between either the content or the users who access the content.

There are several ways to measure the similarity between two items. In this project, I have build a machine learning algorithm that would recommend movies based on a movie the user likes. This Machine Learning model is based on Cosine Similarity.


There are different approaches to build a movie recommender system:
Simple Recommender: this approach ranks all movies based on specific criteria: popularity, awards, and/or genre, then it suggests top movies to users without considering their individual preferences. An example could be Netflix’s “Top 10 in the U.S. Today.”
Collaborative Filtering Recommender: this approach utilizes a user’s past behavior to predict items that the users might be interested in. It considers a user’s previously watched movies, numerical ratings given to those items, and previously watched movies by similar users.
Content-based Filtering Recommender: this approach utilizes the properties and the metadata of a particular item to suggest other items with similar characteristics. For example, a recommender can analyze a movie’s genre and director to recommend additional movies with similar properties.

This Movie recommender system is based on Content-based Filtering.
