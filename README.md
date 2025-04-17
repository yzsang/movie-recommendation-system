# Movie Recommendation System

A content-based and collaborative filtering movie recommender built with Python.

## Features

- Recommend the top 10 most similar movies based on a given movie title  
- Use collaborative filtering to find users with similar taste and identify distinctive recommendations  
- Interactive interface built with `ipywidgets`

## Dataset

Download and extract the [MovieLens 25M dataset](https://files.grouplens.org/datasets/movielens/ml-25m.zip), and place the `ml-25m` folder in the same directory as the notebook.  
Used files: `movies.csv`, `ratings.csv`

## How to Run

1. Install required packages:

```bash
pip install pandas numpy scikit-learn ipywidgets
```

2. Open and run the notebook:

```bash
jupyter lab movie_recommendation.ipynb
```

## Results

Enter a movie title and get recommendations.

Example:

![example](example.png)