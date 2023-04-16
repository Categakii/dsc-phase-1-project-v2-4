**1. Overview
<<<<<<< HEAD
This is phase one project where i was exploring the data to generate insight to business stakeholder (Microsoft)
3. Business Understanding
**Research problem **
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. To solve the problem they need to understand which studios are producing the most successfull movies and explore which genres are performing best at the box office.

4. Include stakeholder and key business questions
The business stakeholder will be Microsoft
Research Questions
To understand which studios are producing the most successfull movies
To explore which genres are performing best at the box office.

*5. Data Understanding and Analysis

Use of the gross_movie dataset and determine the correlation of the total number of movies produced and the gross_domestic revenue for the top 10 companies
Merge the rating and basic dataset and explore the correlation between the genres and average rating.
6. Source of data
Source of data
The following are the data used to perform the task

im.db.zip table :movie_basics and movie_ratings
bom.movie_gross.csv.gz
7. Description of data
/content/bom.movie_gross.csv.gz variables
**title: **the title of the movie

studio: the studio that produced or distributed the movie

domestic_gross: the total domestic (US) box office gross earnings of the movie in US dollars

foreign_gross: the total foreign box office gross earnings of the movie in US dollars

year: the year the movie was released

/content/im.db: ** movie_rating dataset explained

tconst: a unique identifier for each movie (same as in movie_basics)

average_rating: the average rating of the movie, based on user and critic reviews

num_votes: the number of votes/ratings the movie received

distribution: the distribution of ratings, e.g. the number of 1-star, 2-star, 3-star, etc. ratings

/content/im.db: ** movie_basic dataset explained

tconst: a unique identifier for each movie

title_type: the type of title (e.g. movie, short, tvSeries)

primary_title: the primary title of the movie

original_title: the original title of the movie

is_adult: whether the movie is an adult movie (e.g. pornographic content)

start_year: the year the movie was released

end_year: the year the movie stopped running (if a TV series)

runtime_minutes: the runtime of the movie in minutes

genres: the genre(s) of the movie (e.g. Drama, Action, Comedy)
8. Three visualizations (the same visualizations presented in the slides and notebook)

The Scatter plot showing positive correlation between high volume of movies and domestic revenue
gross_movie_corre

10 top studios with highest domestic revenue
gross_movie top 10

10 top genres with highest rating
basic_rating_top 10

9. Conclusion

Based on the analysis, it can be concluded that the top studios producing the most successful movies in terms of gross revenue is DV with the highest revenue.

The data also suggests that there is a positive correlation between a studio's movie production and its gross revenue.

Based on the analysis, we can see that the genres Comedy,Documentary,Fantasy have the highest mean average rating of 9.4 .This suggests that movies in these genres tend to be more highly rated by viewers compared to movies in other genres.

10. Summary of conclusions including three relevant findings**

Microsoft comapany may want to consider partnering with one of the top studios or emulating their successful strategies.

Microsoft can focus on producing a larger quantity of movies in order to increase the chances of generating higher gross revenue.

=======

This is phase one project where i was exploring the data to generate insight to business stakeholder (Microsoft)
3. Business Understanding
**Research problem **

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. To solve the problem they need to understand which studios are producing the most successfull movies and explore which genres are performing best at the box office.

4. Include stakeholder and key business questions
The business stakeholder will be Microsoft
Research Questions
To understand which studios are producing the most successfull movies
To explore which genres are performing best at the box office.

*5. Data Understanding and Analysis

Use of the gross_movie dataset and determine the correlation of the total number of movies produced and the gross_domestic revenue for the top 10 companies
Merge the rating and basic dataset and explore the correlation between the genres and average rating.


6. Source of data
Source of data
The following are the data used to perform the task

im.db.zip table :movie_basics and movie_ratings
bom.movie_gross.csv.gz


7. Description of data
/content/bom.movie_gross.csv.gz variables
**title: **the title of the movie

studio: the studio that produced or distributed the movie

domestic_gross: the total domestic (US) box office gross earnings of the movie in US dollars

foreign_gross: the total foreign box office gross earnings of the movie in US dollars

year: the year the movie was released

/content/im.db: ** movie_rating dataset explained

tconst: a unique identifier for each movie (same as in movie_basics)

average_rating: the average rating of the movie, based on user and critic reviews

num_votes: the number of votes/ratings the movie received

distribution: the distribution of ratings, e.g. the number of 1-star, 2-star, 3-star, etc. ratings

/content/im.db: ** movie_basic dataset explained

tconst: a unique identifier for each movie

title_type: the type of title (e.g. movie, short, tvSeries)

primary_title: the primary title of the movie

original_title: the original title of the movie

is_adult: whether the movie is an adult movie (e.g. pornographic content)

start_year: the year the movie was released

end_year: the year the movie stopped running (if a TV series)

runtime_minutes: the runtime of the movie in minutes

genres: the genre(s) of the movie (e.g. Drama, Action, Comedy)
8. Three visualizations (the same visualizations presented in the slides and notebook)

The Scatter plot showing positive correlation between high volume of movies and domestic revenue
gross_movie_corre
![gross_movie_corre](https://user-images.githubusercontent.com/127992604/232314617-17b6d373-5a6c-4497-8813-a88801815c73.png)

10 top studios with highest domestic revenue
gross_movie top 10
![gross_movie_top_10](https://user-images.githubusercontent.com/127992604/232314649-7f9f4cbb-c1ee-45c2-a075-d5879a96e218.png)

10 top genres with highest rating
basic_rating_top 10
![basic_rating_top_10](https://user-images.githubusercontent.com/127992604/232314657-4d188a64-ba20-446e-8a6d-4d601211a9f7.png)

9. Conclusion

Based on the analysis, it can be concluded that the top studios producing the most successful movies in terms of gross revenue is DV with the highest revenue.

The data also suggests that there is a positive correlation between a studio's movie production and its gross revenue.

Based on the analysis, we can see that the genres Comedy,Documentary,Fantasy have the highest mean average rating of 9.4 .This suggests that movies in these genres tend to be more highly rated by viewers compared to movies in other genres.

10. Summary of conclusions including three relevant findings**

Microsoft comapany may want to consider partnering with one of the top studios or emulating their successful strategies.

Microsoft can focus on producing a larger quantity of movies in order to increase the chances of generating higher gross revenue.

Microsoft should consider genres as an important factor to consider when producing movies, as it can have a significant impact on the viewer's perception of the movie.
