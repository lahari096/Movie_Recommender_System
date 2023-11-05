# Movie Recommender App

Welcome to the Movie Recommender App! This Python-based application utilizes content-based filtering techniques to provide personalized movie recommendations based on user preferences. This README file will guide you through the installation and usage of the application.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Content-Based Filtering](#content-based-filtering)
- [License](#license)

## Installation

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/debanilvb/movie-recommender-system.git
   ```
   
2. Navigate to the project directory:
   ```
   cd movie-recommender-system
   ```
   

3. Launch the project

5. You can use any IDE like Pycharm to run the application

7. Make sure you have streamlit installed

8. In the terminal run the command
     ```
    py -m streamlit run app.py

   ```

## Usage

1. Launch the Jupyter Notebook server and open the `movie_recommender.ipynb` file.

2. Follow the instructions provided within the notebook to specify your movie preferences.

3. The application will process your preferences using content-based filtering techniques and recommend movies that match your preferences.

4. Explore the recommended movie list and find your next movie to watch!

## Dataset

The Movie Recommender App employs a dataset containing information about movies. The dataset includes details such as movie title, genre, director, actors, and plot summaries. The content-based filtering algorithm analyzes this dataset to generate personalized recommendations.

The dataset used in this application is not included in the repository due to its large size. However, you can easily find movie datasets online, such as the MovieLens dataset or IMDb datasets, which can be used to train the recommender system.

## Content-Based Filtering

Content-based filtering is a technique used to recommend items to users based on their preferences and similarities between the items themselves. In the case of this Movie Recommender App, the system recommends movies based on their content, such as genre, director, actors, and plot summaries.

By analyzing the user's preferred movie attributes and finding similarities with other movies in the dataset, the content-based filtering algorithm generates a list of recommended movies that match the user's preferences.
