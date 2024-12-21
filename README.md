# Audience Rating Prediction

This project aims to predict audience ratings for movies using various features such as runtime, genre, director, and other metadata. The machine learning models are built and evaluated using the data in the provided Jupyter Notebook.

## Features
- Handles both numeric and categorical features.
- Implements data preprocessing, including missing value handling and encoding categorical variables.
- Uses regression models such as Linear Regression and Random Forest Regression.
- Evaluates model performance with metrics like Mean Absolute Error (MAE) and R² score.

## Dataset
The dataset includes the following columns:
- `movie_title`: Title of the movie.
- `rating`: Rating of the movie (e.g., PG, R).
- `genre`: Genre(s) of the movie.
- `runtime_in_minutes`: Movie runtime.
- `director`, `studio_name`: Categorical features for director and studio.
- `tomatometer_status`, `tomatometer_rating`, `tomatometer_count`: TomatoMeter details.
- `audience_rating`: Target variable for prediction.

## Dependencies
The project requires the following Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `jupyter`

Install dependencies with:
```bash
pip install -r requirements.txt


