# Movie-Recommendation-System-1-Demographic-Filtering-2-Content-Based-Filtering-3-Collaborative-Filtering
Movie Recommendation  System

## I have built 3 different recommendation engines based on different ideas and algorithms. They are as follows:

* Demographic Filtering: This system used overall TMDB Vote Count and Vote Averages to build Top Movies Charts, in general and for a specific genre. The IMDB Weighted Rating System was used to calculate ratings on which the sorting was finally performed.

* Content Based Recommender: We built two content based engines; one that took movie overview and taglines as input and the other which took metadata such as cast, crew, genre and keywords to come up with predictions. We also deviced a simple filter to give greater preference to movies with more votes and higher ratings.

* Collaborative Filtering: We used the powerful Surprise Library to build a collaborative filter based on single value decomposition. The RMSE obtained was less than 1 and the engine gave estimated ratings for a given user and movie.
