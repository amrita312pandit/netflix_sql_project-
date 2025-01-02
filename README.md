# NETFLIX Movies and TV Shows Data Analysis using SQL

![Netflix_logo](https://github.com/amrita312pandit/netflix_sql_project-/blob/main/LOGO.png)

## Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows data using SQL. The goal is to extract valuable insights and answer various business questions based on the dataset. The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.


## Objectives
   * Compare the number of movies and TV shows.
   * Find the most frequent ratings for both movies and TV shows.
   * Analyze content by release years, countries, and durations.
   * Group and study content using keywords or specific criteria.

## Dataset 
  This Dataset is from the Kaggle
  
  ![Dataset_link](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)


## Schema
   DROP TABLE IF EXISTS netflix;
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
