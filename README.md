Content-Based Movie Recommendation System
A content-based movie recommendation system that suggests movies to users based on the attributes of movies they like. This project uses the TMDB 5000 movie dataset to provide recommendations based on genre, keywords, cast, and crew.

🎬 Project Overview
This recommendation system takes a movie title as input and outputs a list of similar movies. The core idea is to find movies that have similar content features. Instead of relying on user ratings (like in collaborative filtering), this system analyzes the properties of the movies themselves. For example, if you like a superhero movie directed by a specific director, the system will recommend other superhero movies, especially those involving the same cast or crew.

✨ Features
Content-Based Recommendations: Suggests movies based on item attributes.

Feature Analysis: Utilizes movie metadata such as:

Genre

Keywords/Plot Summary

Main Cast

Director and Crew

Similarity Score: Calculates the cosine similarity between movies to find the best matches.

Easy to Use: Simple command-line interface to get recommendations.

📊 Dataset
This project utilizes the TMDB 5000 Movie Dataset, which contains metadata for about 5,000 movies from The Movie Database (TMDb).

The dataset is composed of two CSV files:

tmdb_5000_movies.csv: Contains movie information like budget, genres, homepage, keywords, original language, overview, popularity, release date, revenue, runtime, status, tagline, title, vote average, and vote count.

tmdb_5000_credits.csv: Contains the cast and crew for each movie.

You can download the dataset from Kaggle.

🛠️ Installation
To get this project up and running on your local machine, follow these steps.

1. Clone the repository:

git clone [https://github.com/your-username/Movie-Reccomendation-System.git](https://github.com/your-username/Movie-Reccomendation-System.git)
cd Movie-Reccomendation-System

2. Create a virtual environment (recommended): 

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\

