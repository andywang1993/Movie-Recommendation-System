# Movie-Recommendation-System

##Problem Setting
Nowadays, auto recommendations are everywhere online in our daily life. Movies, TV programs, music, online shopping and so on.
We chose the movie recommendation system as our data mining project.

##Project Definition
By using unsupervised learning methods, we want to analyze each user’s watching and rating history, 
find patterns and use proper models to recommend potentially liked movies for him/her. Specifically, 
for a new user, who have no rating history in our data set, we take our own-built searching and sorting based on user’s input preferences method to find potential recommendations;
for an old user, we take user-based collaborative filtering to find “neighbors” who have similar tastes and then recommend the movies they have watched but our client (the old user who wants recommendations) have not yet.


##Data Description
We have two files for this project.
The file movies.csv contains information about moiveId, title, year(the years it was released), genres(animation, adventure, action...) for 10327 movies.
The file ratings.csv contains information about userId, movieId( the movie that was rated by the user ), ratings( the user give to the movie) for 668 users.
