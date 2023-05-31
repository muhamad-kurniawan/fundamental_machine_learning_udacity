# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Muhamad Kurniawan

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
### 

### What was the top ranked model that performed?
Weighted Ensemble Model

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Add your explanation

### How much better did your model preform after adding additional features and why do you think that is?
It significantly improve the score. The MAE score decrease about 50%.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
There is no improvement. In fact, the score is worse.

### If you were given more time with this dataset, where do you think you would spend more time?
Explore more the dataset. 

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|time_limit|preset|model_hpo|score|
|--|--|--|--|--|
|initial|600|best_quality|default|1.38027|
|add_features|600|best_quality|default|0.55472|
|hpo|600|best_quality|CatBoost, GBM, NN|0.47508|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](model_test_score.png)

## Summary
Feature engineering is important process to improve the score of mcahine learning model.
