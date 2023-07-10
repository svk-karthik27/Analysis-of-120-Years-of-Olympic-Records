# Analysis of 120 Years of Olympic Records

This repository contains an analysis of the [120 Years of Olympic History: Athletes and Results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results) dataset from Kaggle.

## Purpose of Case Study

The purpose of doing analysis on the “120 Years of Olympic History: Athletes and Results” dataset is to gain insights into the trends and patterns in the data. 
By analyzing the data, we can learn more about the performance of different countries, changes in the number of events and athletes over time, and the 
impact of various factors on athletic performance. This information can be used to better understand the history of the Olympic Games and to make 
informed decisions about future events.

## Dataset

The dataset contains historical data on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016. The data is split into two datasets:

1. `athletes`: This dataset contains information about all the players who participated in the Olympics.
2. `athlete_events`: This dataset contains information about all the events that happened over the years. The `athlete_id` column refers to the `id` column in the `athletes` table.

## Analysis

The analysis in this repository explores trends and patterns in the data, including the performance of different countries, changes in the number of events and athletes over time, and the impact of various factors on athletic performance.

The analysis includes solutions to the following problems:

1. Which team has won the maximum gold medals over the years?
2. For each team, print the total number of silver medals and the year in which they won the maximum number of silver medals.
  The output should have 3 columns: `team`, `total_silver_medals`, and `year_of_max_silver`.
3. Which player has won the maximum number of gold medals amongst players who have only won gold medals (i.e., never won silver or bronze) over the years?
4. In each year, which player has won the maximum number of gold medals? Write a query to print the year, player name, and number of golds won in that year.
In case of a tie, print comma-separated player names.
5. In which event and year did India win its first gold medal, first silver medal, and first bronze medal? Print 3 columns: `medal`, `year`, and `sport`.
6. Find players who have won gold medals in both summer and winter Olympics.
7. Find players who have won gold, silver, and bronze medals in a single Olympics. Print player name along with year.
8. Find players who have won gold medals in consecutive 3 summer Olympics in the same event. Consider only Olympics from 2000 onwards.
  Assume summer Olympics happen every 4 years starting in 2000. Print player name and event name.

## Usage

To use this repository, clone it to your local machine and import the datasets into SQL Server. Then, run the queries provided in this repository to solve the problems listed above.

