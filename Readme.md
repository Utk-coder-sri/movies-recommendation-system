# \# Movie Recommendation System

# 

# A web-based Movie Recommendation System developed using Python, Flask, Pandas, and Scikit-learn. The application recommends movies similar to a selected movie using TF-IDF Vectorization and Cosine Similarity.

# 

# \---

# 

# \## Developer Information

# 

# \- Name: Utkrisht Srivastava

# \- Registration Number: 23MIP10139

# 

# \---

# 

# \## Project Overview

# 

# This Movie Recommendation System uses a Content-Based Filtering approach to recommend movies based on genre similarity. Users can select a movie from the available list, and the system instantly suggests similar movies through an interactive web interface.

# 

# \---

# 

# \## Features

# 

# \- Movie recommendation based on genre similarity

# \- Content-Based Filtering

# \- Interactive Flask web interface

# \- Fast recommendation generation

# \- Simple and easy-to-use interface

# \- Ready for deployment

# 

# \---

# 

# \## Technologies Used

# 

# \- Python

# \- Flask

# \- Pandas

# \- NumPy

# \- Scikit-learn

# \- HTML5

# \- CSS3

# \- Gunicorn

# 

# \---

# 

# \## Project Structure

# 

# ```text

# Movie-Recommendation-System/

# │── app.py

# │── recommender.py

# │── movies.csv

# │── ratings.csv

# │── requirements.txt

# │── README.md

# │── templates/

# │     └── index.html

# │── static/

# │     └── style.css

# ```

# 

# \---

# 

# \## Installation

# 

# \### Clone the Repository

# 

# ```bash

# git clone https://github.com/Utk-coder-sri/Movie-Recommendation-System.git

# ```

# 

# \### Navigate to the Project

# 

# ```bash

# cd Movie-Recommendation-System

# ```

# 

# \### Create a Virtual Environment

# 

# ```bash

# python -m venv venv

# ```

# 

# \### Activate the Virtual Environment

# 

# Windows

# 

# ```bash

# venv\\Scripts\\activate

# ```

# 

# Linux/macOS

# 

# ```bash

# source venv/bin/activate

# ```

# 

# \### Install Dependencies

# 

# ```bash

# pip install -r requirements.txt

# ```

# 

# \---

# 

# \## Running the Application

# 

# Start the Flask server:

# 

# ```bash

# python app.py

# ```

# 

# Open your web browser and visit:

# 

# ```text

# http://127.0.0.1:5000

# ```

# 

# \---

# 

# \## Recommendation Algorithm

# 

# The recommendation process follows these steps:

# 

# 1\. Load the movie dataset.

# 2\. Extract movie genres.

# 3\. Convert genres into TF-IDF vectors.

# 4\. Compute cosine similarity.

# 5\. Recommend the five most similar movies.

# 

# \---

# 

# \## Dataset

# 

# This project uses the \*\*MovieLens Latest Small Dataset\*\*.

# 

# The dataset contains:

# 

# \- Movie titles

# \- Genres

# \- Ratings

# 

# \---

# 

# \## Deployment

# 

# To deploy the application using Gunicorn:

# 

# ```bash

# gunicorn app:app

# ```

# 

# \---

# 

# \## Future Improvements

# 

# \- Add movie posters

# \- Implement search autocomplete

# \- Integrate the TMDb API

# \- Add user authentication

# \- Provide personalized recommendations

# \- Include rating prediction

# \- Improve responsive design

# \- Add dark mode support

# 

# \---

# 

# \## License

# 

# This project is developed for educational and learning purposes.

