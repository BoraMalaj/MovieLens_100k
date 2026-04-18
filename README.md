# Movie Recommendation System - Content Based Filtering

## Overview
This project implements a Content Based Filtering recommendation system 
on the MovieLens 100K dataset from Kaggle. As Group 1, the assigned task 
was to build a content based filtering system by extracting movie features 
and building user profiles from historical rating preferences.

## Group
Group 1 - Bora Malaj
Assigned Task: Content Based Filtering

## Dataset
- Source: Kaggle - MovieLens 100K
- Movies : 9742 movies
- Ratings: 100836 ratings from real users
- Tags   : 3683 tags
- Links  : 9742 links to IMDB and TMDB

## Files
| File | Description |
|------|-------------|
| movies.csv | movieId, title, genres |
| ratings.csv | userId, movieId, rating, timestamp |
| tags.csv | userId, movieId, tag, timestamp |
| links.csv | movieId, imdbId, tmdbId |

## Steps Covered
1. Data Loading - all 4 CSV files
2. Feature Extraction - genres, year from title
3. One Hot Encoding of genres
4. Cosine Similarity computation
5. Movie Recommendation Function
6. User Profile building from rating history
7. Personalized recommendations per user
8. Dataset visualizations

## Libraries Used
- pandas, numpy, matplotlib, seaborn, scikit-learn

## Author
Bora Malaj
