# Hybrid Recommender System (Item Based & User Based)
# Business Problem
Use the item-based and user-based recommendation methods to make a guess as to which user the ID belongs to. Make 10 suggestions overall by taking into account
5 suggestions from the user-based model, 5 suggestions from the item-based model, and 10 suggestions from both models.Make a guess for the user whose ID is given,
using the item-based and user-based recomennder methods. Consider 5 suggestions from the user-based model and 5 suggestions from the item-based model and 
finally make 10 suggestions from 2 models.

# Story of Dataset
MovieLens, a service that recommends movies, donated the dataset. It includes ratings along with the turns inside. 
Over 27,278 films are represented by its 2,000,0263 ratings. This data collection was created on October 17, 2016. 
Data from 09 January 1995 to 31 March 2015 and 138,493 users are included. Randomly selected users. 
It is known that each chosen user cast a vote for at least 20 films.

# Variables
For Movie
- movieId : Unique ID assigned to each movie.
- title : Name of the movie.
- genres : Category or genre of the movie.

For Rating
- userid : Unique ID assigned to each user.
- movieId : Unique ID assigned to each movie.
- rating : Rating assigned by the user to the movie (out of 5).
- timestamp : Date and time when

# Tasks
- User-Based

- Task 1: Data Preparation
- Task 2: Determining the Movies Watched by the User to Suggest
- Task 3: Accessing Data and Ids of Other Users Watching the Same Movies
- Task 4: Identifying Users Who Are Most Similar to the User to Suggest
- Task 5: Calculating the Weighted Average Recommendation Score and Keeping the Top 5 Movies

Item-based

- Task 1: Make an item-based suggestion based on the last and highest rated movie the user watched.

