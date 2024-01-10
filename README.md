# Movie Recommendation System

This Movie Recommendation System takes a movie name as an input and recommends you some movies like the input movie based on similarity between them. It also shows you information about input movie and the details of cast who have acted in it. These recommendation system consists of only Hollywood movies.

The details of movie such as (title, genres, poster, status, runtime, release date, IMDB Rating etc) have been fetched from TMDB API https://www.themoviedb.org/documentation/api.

CountVectorizer and PorterStemmer are used to stem the words and create the tags column values into vectors.

To create the recommendation system, cosine_similarity method is used which compares vectors with other vectors and gives similarity between 0 and 1.
