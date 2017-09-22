# kaggle_titanic

Results for the various models:

Logistic Regrssion: 0.75598

Random Forest:      0.

Boosted Gradient:   0.7511


Log loss for the various models:

Logistic Regrssion: 0.4455

Random Forest:      0.

Boosted Gradient:   0.259


## What I learned

This was a good practice with different models.  Overall the gradient boosted model seemed to perform the best, but this model took a significant amount of time to optimize.  The initial creation of the model performed similar to the optimized case  The initial fit of the random forest model was significantly overfit, but once that was corrected the model produced reasonable results.  Even though the logistic model was simple it performed well.


The nature of the cross validation meant there could be significant changes to the hyper parameters, with only small changes to the overall score.
