This is a new [**Android App**].
# This is an android application that shows Lists of movies and Tv Shows with the help of TMDB (the Movie DataBase) api.
# Getting Started
![Image](https://github.com/AsmaJalal/TMDB/blob/main/upcoming%20movie.gif?compress=1&resize=1024x768)
# TMDB
This is an android application that shows Lists of movies, Tv Shows and details of each movie and tv show 
with the help of TMDB (The Movie DataBase) API.

## Features
- Discover Popular, Top Rated and Now Playing movies on TMDb.
- View movie details like release date, rating, tagline and overview inside the app.
- Discover popular, Top Rated, on TV and Airing today TV shows.
- view Tv show details like release date, rating, tagline and overview inside the app.

## Architecture and Tech features
- Fully written in Kotlin language.
- Built on MVVM architecture pattern.
- Uses Android Architecture Components, specifically ViewModel and LiveData.
- Uses Retrofit for making API calls.
- Uses Picasso for image loading.

>**Note**: Make sure you have completed the  Environment Setup instructions till "Creating a new application" step, before proceeding.

## Configuration
In order to run this application, you need to get your own key from TMDb. You can do that by clicking [here](https://www.themoviedb.org/account/signup).

After you get an API key, put that key in ```gradle.properties``` file as follows:
```
API_KEY=your_key_api
```
