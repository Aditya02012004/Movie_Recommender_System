### End to End Content Based Movie Recommendation System Using Streamlit

A Recommender system, or a recommendation system, is a subclass of information filtering system that seeks to predict the “rating” or “preference” a user would give to an item.Simply, Recommender systems aim to predict users’ interests and recommend product items that quite likely are interesting for them. Typically there are three types of recommendation system:

<p align="center">
<img src = "https://github.com/Aditya02012004/Movie_Recommender_System/blob/main/Images/Types-of-Recommendation-Systems.png">
</p>

**Dataset :** 

I will be using (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) the TMDB-5000 dataset for this project simply because it provides me with many columns to work with which have very useful information like the plot of movie, details about the cast, crew, directors, duration of the film,run time etc. This will help me get insights for my data analysis. Furthermore I would be using Cosine Similarity Matrix to determine how similar the documents are irrespective of their size. I will be using features like ‘genres’, ‘Credits’, ‘overview’, ‘Keywords’ from my TMBD-500 dataset for my Content Based Recommendation System.

**Data Preprocessing :**

* Load the dataset from kaggle--movies.csv and credits.csv
* Check if it has any null values or not
* Take the required columns for our analysis
* Do data cleaning
* Use CountVectorizer to convert a collection of text documents to a matrix of token counts
* Use cosine similarity matrix to understand the overview column and identify similar patterns and structure from it
* Save the model weights using pickle

**Deployment :**

Deployment is done using streamlit and make a web application movie Recommendation System.
<p align="center">
<img src = "https://github.com/Aditya02012004/Movie_Recommender_System/blob/main/Images/Recommendation_System.jpg">
</p>

**Future Work :**

In future , I will try to use Collaborative Filtering and Hybrid Recommendation System. Also I will try to add description about the movies and  trailer of the particular recommended movies using API fetch.
