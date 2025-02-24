# Lumaa-spring-2025
## Author: Ahyo Falick
## Date: 2/23/2025

## Overview
This is my submission for the Lumaa AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation. For this task, I used python to build a recommender system that takes in a user input and outputs a list of recommended movies based on a similarity score. The implementation of this system involved converting relevant movie information into Term frequency-inverse document frequency (TF-IDF) vectors and computing the cosine similarity.

## Data Set
I used the TMDB 5000 Movie Dataset generated using The Movie Database API. The full data set I used can be found in csv form at https://raw.githubusercontent.com/Ahyo2/lumaa-spring-2025/refs/heads/main/tmdb_5000_movies.csv

For the purposes of this assignment I used only 4 of the 20 features and only the first 500 rows of the data set.

## Setup
This task was completed in a Jupyter notebook labeled Recommender.ipynb

**Python version:** Python 3

**Virtual Environment:** Jupyter

**No dependencies required**

## Running
To run this code, download and open the Recommender.ipynb file in a jupyter notebook and run the cells in order.

This notebook includes all of the code that was used to load and clean the dataset and build the recommender, as well as some sample outputs and my salary expectations.

## Results
Given a user query in the form of a string, my functions will output the top 5 recommended movies ranked in order of their similarity score along with the similarity score. The following is a simple example:

For the following user input,

`user_input = "I want a disaster movie set in the future"`

The output is
```
-----------------------------------
Top 5 movie for: 'I want a disaster movie set in the future'
0: Cloud Atlas, 0.08
1: The Time Machine, 0.08
2: Terminator Genisys, 0.08
3: Mad Max: Fury Road, 0.08
4: 2012, 0.07
```
