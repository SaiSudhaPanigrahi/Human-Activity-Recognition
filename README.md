# Human-Activity-Recognition

In this project, we tried to perform Human Activity Recognition using time-series numerical data generated by a Wireless Sensor Network (WSN). The dataset consists of 7 different activities!

During this project, we applied several important techniques which are known to work well in time-series classification problems. For example, one of those techniques propose that we split our time-series dataset into multiple time-series of smaller length than the original one in order to create more artificial instances for our model. The best split was chosen each time by using k-fold CV.

Additionally, during this project, we tried to apply several machine learning algorithms combined with feature selection methods. As suggested, the feature selection took place inside the loop of the k-fold CV in order to avoid the bias in our model. Among the algorithms applied, some of them were:

1) Logistic Regression with Recursive Feature Elimination (RFE)
2) Logistic Regression with L1 regularization
3) Naive Bayes with Gaussian likelihood
4) Multinomial Naive Bayes


   **Table: Final Results**



|      Model 			| Best Time Series Split     	| CV Accuracy  | Test Accuracy |  
|:-----------------	|:-----------	|:-----------	|
| Logistic Regression with $$l_1$$ Regularization        | 2   	| 84.75 %        | 84.21 %        | 
| Naive Bayes with Gaussian Likelihood          	| 46.66 %        | 0.533        |
| Multinomial Naive Bayes           	| 49.06 %        | 0.563        |
