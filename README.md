# basketball-analytics


*author*: Che Hoon, Jeong
This project is currently in development


# Introduction

This project explores the three point strategy in the NCAA. In recent years, numerous NBA teams have utilized found success by utilizing the three point shot. Given this phenomenon, this project investigates if the same trend is reflected in the NCAA Division 1 league.


# Data

The NCAA boxscore and play-by-play data was retrieved from the Google Cloud BigQuery database uploaded by SportsRadar and the NCAA. Command used is available in the `sqlcommands` file under the Code directory. Data of NCAA is not uploaded in this repository because it exceeds the data size limit.

# Code Files

|File Name.    |Description|
|--------------|-----------|
|analysis.ipynb|Python code that generates shot chart visualization|
|ncaa-analysis.rmd|R markdown file that creates Logistic Random Effects Mixed Model of NCAA boxscore data|
|sqlcommand.rtf |Text file of SQL command to extract data from Google BigQuery Database of NCAA *shot* data|
|sqlcommand.rtf | Text file of SQL command to extract data from Google BigQuery Database of NCAA *boxscore* data|


# Versions and Packages

|Name| version number|
|----|---------------|
|python|3.9.12|
|R|4.2.1|
|Stata|Stata B/E 17.0|
|Matplotlib|3.5.1 |
|Pandas|1.4.2|


