# Logistic-Regression-and-Optimized-Logistic-Regression-Explained


## Learnign Curve
It is clear from the figure that variance is very low because gap between training recall and validation recall throughout the curve is small.
Since validation recall is almost 1, we can say that our model is having very low bias and it is able to predict almost all the malignant variables correctly.

## Standard Logistic Regression Model
Our model was able to predict all the Benign variables correctly.
Out of 48 Malignant, our model was able to predict 46 correctly and 2 incorrectly.
Precision, recall and F1-scores value is 1.
Which states that our model is highly accurate

## Optimized Logistic Regression Model

In optimized model, out of 48 Malignant samples, it was able to predict 47 correctly and 1 was misclassified. 
Whereas, in logistic regression, it was 2
Here, we are more concerned about if patient has a cancer than we should be able to predict it correctly. In terms of this situation, Optimized model is performing well than Standard model by means of 1 entry. 
Although, accuracy, F1 score and precision is same as Standard model. I would still choose optimized model over standard.


