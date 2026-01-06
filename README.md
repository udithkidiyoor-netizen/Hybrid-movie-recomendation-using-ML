# Hybrid-movie-recomendation-using-ML
This repository contains a hybrid movie recommendation system that utilizes K-Means clustering and content-based filtering (TF-IDF &amp; cosine similarity) to suggest movies similar to a given input. It processes metadata from IMDb's Top Movies, including genres, ratings, and crew details, to provide personalized recommendations.

## Objective
Finding a great movie to watch can be overwhelming. This project builds a smart recommendation system that suggests movies based on their genres, content, and clustering.

## Methodology
* Data preperation
* KMeans Clustering
* TF-IDF, Cosine similarity content based   filtering
  
## Example Recommendation Output
### Input movie
      movie_name = "Iron Man"
      recommended_movies_df = recommend_movies(movie_name, n=5)
      print(f"Recommended movies similar to '{movie_name}':")
      print(recommended_movies_df)

### Output
Recommended movies similar to 'Iron Man':

            primaryTitle           averageRating   rank
      2448  Iron Man 3                7.1          2449
      3283  Iron Man 2                6.9          3284
      4590  The Man in the Iron Mask  6.5          4591
      1087  Spider-Man 2              7.5          1088
      1367  Spider-Man                7.4          1368
