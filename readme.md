# PornHub Analysis

In this paper we aim to determine the machine learning model most  fit for predicting the number of views for a pornographic video. 

For this purpose we did the following:

1. We test if the prediction of the model can be enhanced, when features from thumbnail images are added as features. 

2. We employ public data from www.kaggle.com through the API. A bag-of-words model is used both on the titles of the videos and the categories. Only videos with English titles are used, and we control for the presence of either a male or female name in the title. 

3. OLS, LASSO, the elastic net and a random forest regression is used to prediction. The choice of hyperparameters is made based on a 10-folds cross validation. 

4. We find that the best performing model based on both computational time and the mean squared error is the LASSO. However, we are not able to conclude that the performance of the LASSO is enhanced by the thumbnail features.

##### The repository consist of:
- Written analysis: se the pdf file *paper.pdf*
- Code: see the jypyter notebook file *code.ipynb*


