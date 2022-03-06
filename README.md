# Ad Click Prediction
A logistic regression model predicting whether a user will click on an ad.

## Description
The `logistic_regression.ipynb` notebook contains:
* visualization of the data (histograms, jointplots, and pairplots showing the relationships between features),
* model training, making predictions, and evaluation of the model performance with final insights.

## The Data
The dataset consists of the following features:
* `Daily Time Spent on Site` (average, in minutes),
* `Age` (in years),
* `Area Income` (average annual income of geographical area of the user in USD),
* `Daily Internet Usage` (average, in minutes),
* `Ad Topic Line` (headline of the advertsement),
* `City` (user's city of residence),
* `Male` (whether the user is male (1) or female (2)),
* `Country` (user's country of residence),
* `Timestamp` (time in which the user clicked on an ad (if `Clicked on Ad` equals `1`) or closed the site (if `Clicked on Ad` equals `0`)),
* `Clicked on Ad` (`1` if the user clicked on an ad, otherwise `0`).
