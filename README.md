# SIMPLE MOVIE RECOMMENDATION SYSTEM

## Table of contents

- [Overview](#overview)
  - [Project Structure](#project-structure)
- [Data](#data)
  - [Content based filtering](#content-based-filtering)
  - [Collaborative filtering](#collaborative-filtering)
- [Continued development](#continued-development)
- [Author](#author)

## Overview

### Project Structure

This project is made for movie recommendations. Based on the content of the movies or the rating of the user from existing data, this project can predict or recommend for the current user movies that could be interesting to them.
There are 2 different ways to recommend movies in this project:
+ Content Based Filtering (using TF-IDF and cosine similarity to calculate the similarities between the movies' content)
+ Collaborative Filtering (using K-NN and SVD with the help of Surprise library)

There are 4 main steps for each way:
+ Data preprocessing
+ Studying the data
+ Implementation of the recommendation system
+ Running the program and displaying the final results.

## Data

All the data that I use in this project can be found in the data folder 

### Content based filtering

For the content based filtering. I'm using the credits.csv (for the names of actors, directors), keywords.csv (for the movies' keywords) and the movie_metadata.csv (for the details of the movies).

### Collaborative filtering

As for the collaborative filtering. I'm using the ratings_small.csv (for the users' ratings), links_small.csv (for the connections between the csv files) and the movie_metadata.csv


## Continued development

- Maybe this is just a simple project but I did the best I could do (atleast for now). It's fun to know more about Python and the algorithms in machine learning.


## Author

- Website - [BeingX234 or Hieu Nguyen](https://github.com/BeingX234)

