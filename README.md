# machine-learning-challenge

## Introduction
A few simple machine learning and neural network models have been created to evaluate data collected by the Kepler Telescope.  The models attempt to predict the Kepler Object Of Interest (KOI) classification ("CONFIRMED", "FALSE POSITIVE", "CANDIDATE") of each object.  The KOI disposition is is a classification given to deep space objects that have the potential to be planets.

## Resources
* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

## Technologies
1. Python
    * pandas
    * sklearn
    * joblib
    * tensorflow

## Results
1. newton-cg model
    * A linear model that was the fastest performing model and scored fairly well.

2. liblinear model
    * A linear model that was quite a bit slower in performance, but scored almost as well as newton-cg.

3.  neural network
    * A tensorflow keras model that with the best score of the three models.