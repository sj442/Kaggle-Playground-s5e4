# The podcast listening time prediction challenge
This challenge is featured in [Kaggle's Playground series](https://www.kaggle.com/competitions/playground-series-s5e4/overview) for April 2025. 

The goal is to predict listening time of a podcast based on features such as podcast name, episode title, genre, host and guest popularity, duration etc. 

Evaluation Metric: Root Mean Squared Error (RMSE)

RMSE is defined as:


$\text{RMSE}(y, \hat{y})$ = \$sqrt{\frac{\sum_{i=0}^{N - 1} (y_i - \hat{y}_i)^2}{N}}$

where $\hat{y}_i$ is the predicted value and $𝑦_i$ is the original value for each instance 𝑖

The dataset for this competition (both train and test) was generated from a deep learning model trained on the [Podcast Listening Time Prediction](https://www.kaggle.com/datasets/ysthehurricane/podcast-listening-time-prediction-dataset) dataset. 
Feature distributions are close to, but not exactly the same, as the original.
