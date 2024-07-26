# Movie Reccomendation System

## Overview

- The Movie Recommendation System is a machine learning-based application that provides personalized movie recommendations to users. It utilizes collaborative filtering techniques to analyze user preferences and similarities among movies to generate accurate and relevant recommendations

```bash
    live site present in the Deployments section is just a demo of the website
 ```


## Features

- *Personalized Recommendations*: Suggests movies based on user preferences and viewing history.
- *Collaborative Filtering*: Recommends movies by analyzing similar users' viewing patterns.
- *Content-Based Filtering*: Provides suggestions based on the movie’s attributes, such as genre, director, and keywords.
- *User Profiles*: Allows users to create and update profiles with their viewing preferences.
- *Search Functionality*: Enables users to search for movies by title, director, or genre.
- *Ratings and Reviews*: Users can rate and review movies to improve recommendation accuracy.
- *Movie Details*: Provides detailed information about each movie, including summaries, cast, and crew info.
## Technologies Used

- *Python*: The programming language used for development.
- *Scikit-learn*: For implementing machine learning algorithms.

## Running the model

1. *Download the dataset:*

    tmdb_5000_credits
   ```bash
    (https://www.kaggle.com/code/kerneler/starter-tmdb-5000-credits-26649e12-5/input)
   ```
    tmdb_5000_movies
   ```bash
    https://www.kaggle.com/code/kerneler/starter-tmdb-5000-movies-f99d3607-2
   ```
    

3. *Run the Untitled.ipynb:*

    to place the pickle files:

    The pickle files are placed as
    {similarity.pkl, movie_dict.pkl}
    
    

## Installation 

To run this model, you need to have Python and streamlit installed on your system. Follow these steps to set up the project:

1.  *Install Dependencies:*


    Ensure you are in the project directory:

    ```bash
    pip install streamlit
    ```

2. *Run the Script:*

    Start the model by running the script:

    ```bash
    streamlit run app.py
    ```

3. *Instructions:*

    - *Search Movies*: Use the search bar to find movies by title, director, or genre.
    - *View Recommendations*: Access personalized movie recommendations on the home page.
    - *Rate and Review*: Rate and review movies to improve future recommendations.
    - *Create Watchlists*: Manage your own watchlists and explore trending movies.

## Additional Notes
- *Dependencies*: Ensure Python and necessary libraries are installed.
- *Environment*: It's recommended to use a virtual environment for dependency management
