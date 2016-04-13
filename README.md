# Machine Learning Nano Degree
## Project1 - Predicting Boston Housing Prices
### Project Highlights
  This project shows:
  * How I use NumPy to investigate the latent features of a dataset.
  * How I analyze various learning performance plots for variance and bias.
  * How I determine the best-guess model for predictions from unseen data.
  * How I evaluate a model’s performance on unseen data using previous data.
  
### Project Report Questions
  * Q : Why do we split the data into training and testing subsets for our model?
    * A : Our goal is to make our model generalize beyond the data instances used to train models. So we want to evaluate the model to estimate the quality of its pattern generalization for data the model has not been trained on. In order to do that, we need to use some of the data that we already know the answer for as a proxy for future data. That’s why we split the data into training and testing subsets.
  * Q : What is cross-validation, and how is it performed on a model? Why would cross-validation be helpful when using grid search?
    * A : Cross validation is an iterative process where train/test sets are randomly generated multiples times in order to evaluate the algorithm at each split, the results are then averaged over the splits. Cross validation would be helpful when a dataset is limited in size cross validation becomes extremely useful as it allows for an extensive exploitation of available data allowing assessing the real potential of our algorithm in terms of performance metrics.
