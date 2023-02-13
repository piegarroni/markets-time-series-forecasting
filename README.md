# Time-Series Forecasting Model for Linear Growth Coefficient Predictions



This repository contains a machine learning model that, taking into consideration the current and the past market status, can predict the stock market growth on the long(er) term (6-12 months). A similar model can also be adapted to bonds, gold, currencies and many other commodities and securities that trade in high volumes.ed on a dataset of growth coefficients of various organisms and can be used to predict the growth coefficients of new organisms.

This will be eventually used as a help for hedge fund's portfolio managers (decision makers), even though it can't have access to the same amount of information about the market as an experienced professional investor, but what it can do is measure what it currently know about
The market and give an unbiased prediction about the coefficient of growth of the future months.

The coefficient of growth is the coefficient of the linear regression of the future stock market returns.

## Disclaimer
This model is not meant to be implemented as a bot, it will not be able to automatically trade, the scope is to suggest the traders the next moves to make.

## Prerequisites
Before using the model, you will need to have the following packages installed:

* NumPy
* Pandas
* scikit-learn
* matplotlib (for visualizing the results)
* keras

## Data

## Model

## Evaluation
The model's performance was evaluated by predicting a small portion of the last part of the dataset.
This method was adopted to avoid overlap between train and test time serie

## Contact
If you have any questions or suggestions, feel free to open an issue in this repository or contact the maintainers directly.
