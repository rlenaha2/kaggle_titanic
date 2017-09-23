# Model Creation for the Titanic Dataset on Kaggle

Results for the various models:

Logistic Regrssion: 0.75598

Random Forest:      0.7464

Boosted Gradient:   0.77033


Log loss for the various models:

Logistic Regrssion: 0.4455

Random Forest:      0.2813

Boosted Gradient:   0.3416


## What I learned

This was a good practice with different models.  Overall the gradient boosted model seemed to perform the best.  The initial fit of the random forest model was significantly overfit, but once that was corrected the model produced reasonable results.  Even though the logistic model was simple it performed well.


The nature of the cross validation meant there could be significant changes to the hyper parameters, with only small changes to the overall score.  Also depending on which data was selected to which split could have a small effect on the final hyperparameters and the results.  Finding the optimal number of estimators outside of the grid search reduced the amount of time significantly.
