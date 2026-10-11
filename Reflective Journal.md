Elda's Entry

In the linear regression model, I learned to create and train a model to predict passenger fares. I also learned that mean squared error
compares predicted fares with actual fares, while the root mean squared error makes a prediction error easier to understand using dollars.
The lab also showed me that preparing complete data, choosing useful features, and measuring errors are important when checking a model's
performance, all of this gave me a better foundation for evaluating and building models for other real-world problems.


Xinyu's Entry:

I completed this lab on Regression vs. Classification in Machine Learning. My specific experiments for the lab were to train and test a Logistic Regression model using the Titanic data. I used the training set to train the model, then tested it using the test set. The model correctly predicted the survival of about 75% of the passengers in the test data set (accuracy = 74.83%). Why wasn’t it 100%? Note that simply running the code does not necessarily mean that the model made correct predictions. This is a common source of confusion, especially for beginners.

As I stated above, the model doesn’t have to get every prediction right, even though the code completed. From what I can gather, the reason for the percentage is that we only had 3 features for the model to work with to get the best results for predicting the survival of the passengers. Using the passengers’ fare and family size may result in a higher accuracy.

Accuracy is one of the metrics to measure the performance of a classification model, and it returns the percent of correctly classified instances. The accuracy I got from my model of 74.83% only returns whether each instance was classified correctly or not. A confusion matrix, precision, and recall would be good things to explore further to get more information about how my model did for each of the passengers.

The lessons learned in this lab also taught me another important lesson. That is, you must run the notebook cells in the correct order to get the expected results. In the initial attempt, there were some syntax errors in the data preparation code. Also, when I tried to create the DataFrame from the given data, it did not get created for some unknown reason. Once these errors were corrected and the correct notebook cells were executed in order, the model was working fine. I also came to realize that machine learning involves several steps to achieve a goal. In this lab, the steps involved in achieving the goal were data preparation, training the model, and evaluating the model.
