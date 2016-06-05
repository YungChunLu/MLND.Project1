# Machine Learning Nano Degree
## Project1 - Predicting Boston Housing Prices
![alt text](https://github.com/ArthurLu/MLND.Project1/blob/master/Cover%20Picture.png "Project1 Cover Picture")

### Project Highlights
  * Used NumPy to investigate the latent features of a dataset.
  * Analyzed various learning performance plots for variance and bias.
  * Determined the best-guess model for predictions from unseen data.
  * Evaluated a model’s performance on unseen data using previous data.

### General Descriptions
  * Built a model to predict the value of a given house in the Boston real estate market using various statistical analysis tools.
  * Identified the best price that a client can sell their house utilizing machine.

### Project Report Questions
  * Q : Why do we split the data into training and testing subsets for our model?
    * A : Our goal is to make our model generalize beyond the data instances used to train models. So we want to evaluate the model to estimate the quality of its pattern generalization for data the model has not been trained on. In order to do that, we need to use some of the data that we already know the answer for as a proxy for future data. That’s why we split the data into training and testing subsets.
  * Q : What is cross-validation, and how is it performed on a model? Why would cross-validation be helpful when using grid search?
    * A : Cross validation is an iterative process where train/test sets are randomly generated multiples times in order to evaluate the algorithm at each split, the results are then averaged over the splits. Cross validation would be helpful when a dataset is limited in size cross validation becomes extremely useful as it allows for an extensive exploitation of available data allowing assessing the real potential of our algorithm in terms of performance metrics.

## Licence
The content of this repository is licensed under [MIT License](https://github.com/ArthurLu/MLND.Project1/blob/master/LICENSE.txt)
