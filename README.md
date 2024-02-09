# Movie and Song Recommendation

This repository contains the code for the Movie and Song Recommendation project. The project is developed by Harsh, Aditya Jagdale, and Vimal Jayant S. It utilizes the TMDB API and the MusicAPI to generate personalized movie recommendations and provide Spotify album links based on user input.

## Features

- **Spotify URL Generation**: The `songs()` function retrieves the Spotify album URL for a given movie using the MusicAPI.
- **Movie Information Retrieval**: The `movie_info()` function retrieves information about a movie based on user input using the TMDB API.
- **Similar Movie Recommendation**: The `movie_similar()` function recommends similar movies based on a given movie using the TMDB API.
- **User Interaction**: The `main()` function takes user input for a desired movie title and displays the movie information, Spotify album link, and similar movie recommendations.

## Installation

1. Clone the repository:

    ```shell
    git clone https://github.com/your-username/Movie-and-Song-Recommendation.git
    ```

2. Install the required dependencies:

    ```shell
    pip install tmdbv3api requests
    ```

## Usage

1. Obtain a TMDB API key from [https://www.themoviedb.org/](https://www.themoviedb.org/).
2. Import the necessary modules into your Python project:

    ```python
    from tmdbv3api import Movie
    from tmdbv3api import TMDb
    import requests
    import json
    ```

3. Set the TMDB API key:

    ```python
    tmdb_api_key = 'your-tmdb-api-key'
    tmdb = TMDb()
    tmdb.api_key = tmdb_api_key
    ```

4. Call the `main()` function to run the program and follow the prompts to input a desired movie title.

> Note: Make sure to replace `'your-tmdb-api-key'` with your actual TMDB API key.

## Contributors
- Vimal Jayant S. 
- Harsh 
- Aditya Jagdale 

