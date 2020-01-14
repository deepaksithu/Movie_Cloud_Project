# :cloud::movie_camera::cloud: Movie Cloud Project -  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/deepaksithu/Movie_Cloud_Project/master?filepath=Gathing.ipynb)
Movie Gathering Project is a project for the Udacity Data Analyst Nanodegree. The project creates a data set of ranked movies which can be used to generate a word cloud.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements) 
- [Issues](#issues) 
- [Contact](#contact)

## Overview
This project uses data gathering techniques such as web scrapping to generate a word cloud for the top 100 rated movies on Rotten Tomatoes using the reviews of each film from Roger Ebert to fill in the words and the posters for each film for the shape of the clouds. An initial data set is created which contains columns for the title of the movie, the URL of the Roger Ebert review, and the text of the review. A second data set is then created with the ranking of each film, their title, and a URL for their poster from Wikipedia.

## Requirements
This code depends on the following libraries:
1. `requests`
2. `os`
3. `glob`
4. `pandas`
5. `wptools`
6. `Image` from `PIL`
7. `BytesIO` from `io`

Additionally, the file `relational_databases_in_python.ipynb` depends on the library `create_engine` from `sqlalchemy`.

In addition to these, the Jupyter Notebook assumes that the data set, `bestofrt_master.csv`  is in the project folder.

The Binder badge above can be used to explore an executable environment for this project. 

## Issues

- organize project and note files
- review project and notes for further application
- generate word cloud using `word_cloud`

## Contact
You can get in touch with me on LinkedIn [![LinkedIn Link](https://img.shields.io/badge/Connect-deepaksithu-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect
)](https://www.linkedin.com/in/deepaksithu) <br>
give me that choice follow on Github      ![GitHub followers](https://img.shields.io/github/followers/deepaksithu?style=social)<br>
or email me at deepaksithu@gmail.com.
