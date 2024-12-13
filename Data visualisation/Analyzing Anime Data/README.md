# Anime Data Analysis: Ratings, Popularity, and Longest-Running Series

<p align="center">
    <img src="https://assets1.ignimgs.com/thumbs/userUploaded/2019/11/22/36190303top25animeblogroll-1574476919122.jpg" width="250">
</p>

## Overview
This notebook explores an anime dataset to uncover key insights related to:

1. **Top 5 Highest Rated Animes**  
   We plot the top 5 highest-rated animes based on the average user ratings.
   
2. **Top 5 Most Rated Animes**  
   The top 5 animes with the most user ratings are visualized to understand their popularity.

3. **Episodes vs. Ratings**  
   A scatter plot that explores the relationship between the number of episodes and average ratings for the animes.

4. **Longest-Running Series vs. Ratings**  
   A bar chart visualizing the longest-running series based on the number of episodes and their average rating.

## About this Dataset

### Context
This dataset contains information on user preference data from **73,516 users** on **12,294 anime**. Each user is able to add anime to their completed list and give it a rating. This dataset is a compilation of those ratings.

### Content

#### **Anime.csv**
- **anime_id**: myanimelist.net's unique ID identifying an anime.
- **name**: Full name of the anime.
- **genre**: Comma-separated list of genres for this anime.
- **type**: Type of anime (e.g., movie, TV, OVA).
- **episodes**: Number of episodes in this show (1 if it's a movie).
- **rating**: Average rating out of 10 for this anime.
- **members**: Number of community members who are part of this anime's "group."

#### **Rating.csv**
- **user_id**: Non-identifiable randomly generated user ID.
- **anime_id**: The anime that this user has rated.
- **rating**: Rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating).
