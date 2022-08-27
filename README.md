# microsoft_film_studio
## Description 
The study was conducted to help Microsoft break into the film business. The objective was to determine what kinds of movies are currently performing the best at the box office based on genre, average rating and release time.
## Overview
I've been assigned to help Microsoft break into the film business. My objective was to determine what kinds of movies are currently performing the best at the box office and to inform Microsoft's new movie company executives of my results. My investigation of the film industry, which I accomplished by collecting data, using descriptive statistics, and creating visualizations, has demonstrated that a higher budget is associated with a bigger gross revenue return. Going by the findings from the data, a studio is bound to make about 2.4 billion US dollars on an Action/Adventure/Sci-Fi movie released in May, taking into account its production cost, thus the movie studio will likely succeed according to this metric. In terms of number of viewers, Drama movies are the most wactched according to the study and Documentary movies are the most occuring in the list of top 50 rated movies with a count of 11, follwed closely by Drama with 10 and Action/Adventure/Sci-Fi with 3 counts.
## Business Understanding
Microsoft desires to venture into the movie production industry and they have set up a studio. The role that this study has assumed is that of a data scientist who is tasked with shedding light on the movie industry to determine which kind of movies perform best at the box office. The ultimate goal is recommending a movie industry investment strategy to Microsoft.

The anaysis is based upon four main questions:

Which genre combination and independent genre is most popular?
Which month is lucrative to release the movies?
What is the relationship between production budget and revenue earned?
How much would you expect to spend on a good movie?
## Data Understanding
The study made use of data from two sources in order to perform an analysis of the movie industry:

IMDB: This data source provides access to an IMDB SQL database that the study queried using SQLite in order to obtain movie_basics and movie_ratings. The movie_basics table contained data on movie id, primary title, original title, genre, release year and runtime minutes while the movie_ratings table contained data on movie id, average ratings and number of votes. The study then joined the two tables using the primary key of movie id.
TheNumbers: This source provides access to data on movie title, release date, production budget, domestic gross revenue and worldwide gross revenue.
The study first perfomed a merger of movie_basics with movie_ratings then a merger of the first merger with data ffrom TheNumbers.
## Data Collection
The data was collected from two sources. The first is the IMDb database that the study queried using SQLite in order to obtain movie_basics and movie_ratings. The movie_basics table contained data on movie id, primary title, original title, genre, release year, and runtime minutes while the movie_ratings table contained data on movie id, average ratings, and the number of votes. The study then joined the two tables using the primary key of the movie id. From The Numbers, the study had access to data on movie titles, release dates, production budgets, domestic gross revenue, and worldwide gross revenue.
## Data Description
