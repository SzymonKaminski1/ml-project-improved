# ML project improved
This project is about the same problem as "ml-project" in my repository i.e. choosing best model for predicting cancer medicine perfomace. Data set consists of variables containing information about cancer genes expression and a variable 'Y' showing medicine effect. 'Y' values are in [0,1] interval and the lower 'Y' value is the better medicine is performing. \
In my way of improving it I focused on ElasticNet method. It consists of
- data standardization
- preliminary function that uses Ridge, Lasso and ElasticNet methods to obtain view on how these algorithms perform on given data set.
- further checking for, in my opinion, best candidate for model and its parameters.

These elements enbled me to create more efficient way to train these models and eventually get smaller MSE value on the training data set. Unfortunately I am not able to check my results on test set any more.\
Train and test data is stored in: https://drive.google.com/drive/folders/1ADea54376PHXMwRHeteK6h4kqqPxS5af?usp=sharing
