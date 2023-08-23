# Project-7-Movie-Data-Analysis

I. Central Question

How do factors such as rating, genre, distributor, director/actor, cast size, crew-size and run-time affect a movie’s box office performance, as measured by its total revenue? 

II. Goal & Focus 

This project aims to determine the relationship between said variables and a movie's performance at the box office. By finding out how each variable correlates to total revenue, we hope to have a better understanding of what factors greatly influence the success of a movie. We chose to analyze genre, distributor, director/actor, cast size, crew-size, and run-time because datasets pertaining these indicators are usually large in size and readily available. With regard to ranking, we opted for IMDB’s data instead of Rotten Tomatoes’ because IMDB’s ratings are typically averaged over a large sampling size. In addition, it better reflects the opinion of “average” movie goers, which is what we want to capture, instead of opinions from movie critics, which can greatly deviate from general consensus. 


III. Datasets 

Dataset 1: Movie Dataset (Kaggle) 

A comprehensive JSON file containing information of more than 40000 movies with variables ranging from: genres, budget, revenue, production companies, runtime, cast size, crew size	, director and so on. 

Dataset 2:  The Numbers 

This website contains information about top-grossing movies of each year, top-grossing distributors, top-grossing genres, top-grossing production methods, top-grossing sources, ....) We intend to scrape this website’s HTML to obtain data tables. 

Dataset 3: IMDB

This dataset contains information about the 250 highest rated movies of all time on IMDB.  The reason we chose this source is because we can use the Beautiful Soup package from Python to scrape data from the website’s HTML. With the scraped data in the form of a table, we can utilize the rating of movie-goers to analyze the public opinion of movies and how that correlates (or contribute) to a movie’s success at the box office. 

IV. Implementation 

We intend to answer our central question by finding the correlation between each indicator (aforementioned) and revenue. Below we will list the operations we intend to perform on each independent variable. 
