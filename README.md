# Logistic-_-regression

## What is Logistic Regression?
Logistic regression is used for binary classification where we use sigmoid function, that takes input as independent variables and produces a probability value between 0 and 1.

For example, we have two classes Class 0 and Class 1 if the value of the logistic function for an input is greater than 0.5 (threshold value) then it belongs to Class 1 it belongs to Class 0. It’s referred to as regression because it is the extension of linear regression but is mainly used for classification problems.

## Key Points:

- Logistic regression predicts the output of a categorical dependent variable. Therefore, the outcome must be a categorical or discrete value.
- It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.
- In Logistic regression, instead of fitting a regression line, we fit an “S” shaped logistic function, which predicts two maximum values (0 or 1).

## Logistic Function – Sigmoid Function
- The sigmoid function is a mathematical function used to map the predicted values to probabilities.
It maps any real value into another value within a range of 0 and 1.
- The value of the logistic regression must be between 0 and 1, which cannot go beyond this limit, so it forms a curve like the “S” form.The S-form curve is called the Sigmoid function or the logistic function.
- In logistic regression, we use the concept of the threshold value, which defines the probability of either 0 or 1. Such as values above the threshold value tends to 1, and a value below the threshold values tends to 0.

# Types of Logistic Regression
On the basis of the categories, Logistic Regression can be classified into three types:
- Binomial: In binomial Logistic regression, there can be only two possible types of the dependent variables, such as 0 or 1, Pass or Fail, etc.
- Multinomial: In multinomial Logistic regression, there can be 3 or more possible unordered types of the dependent variable, such as “cat”, “dogs”, or “sheep”
- Ordinal: In ordinal Logistic regression, there can be 3 or more possible ordered types of dependent variables, such as “low”, “Medium”, or “High”.

Sigmoid Function
Now we use the sigmoid function where the input will be z and we find the probability between 0 and 1. i.e. predicted y.

![image](https://github.com/Rohitbachchhe17/Logistic-_-regression-/assets/163370274/af8b250a-3447-427c-988e-dff3d510e730)

                
![image](https://github.com/Rohitbachchhe17/Logistic-_-regression-/assets/163370274/59799260-7b6b-4576-a2ed-10ff00020504)


As shown above, the figure sigmoid function converts the continuous variable data into the probability i.e. between 0 and 1. 

## How to Evaluate Logistic Regression Model?
We can evaluate the logistic regression model using the following metrics:
# 1) Accuracy: Accuracy provides the proportion of correctly classified instances.
Accuracy = \frac{True \, Positives + True \, Negatives}{Total}   

# 2) Precision: Precision focuses on the accuracy of positive predictions.
Precision = \frac{True \, Positives }{True\, Positives + False \, Positives}  

# 3) Recall (Sensitivity or True Positive Rate): Recall measures the proportion of correctly predicted positive instances among all actual positive instances.
Recall = \frac{ True \, Positives}{True\, Positives + False \, Negatives}   

# 4) F1 Score: F1 score is the harmonic mean of precision and recall.
F1 \, Score = 2 * \frac{Precision * Recall}{Precision + Recall}  

# 5) Area Under the Receiver Operating Characteristic Curve (AUC-ROC): 
The ROC curve plots the true positive rate against the false positive rate at various thresholds. AUC-ROC measures the area under this curve, providing an aggregate measure of a model’s performance across different classification thresholds.

# 6) Area Under the Precision-Recall Curve (AUC-PR): 
Similar to AUC-ROC, AUC-PR measures the area under the precision-recall curve, providing a summary of a model’s performance across different precision-recall trade-offs.


![image](https://github.com/Rohitbachchhe17/Logistic-_-regression-/assets/163370274/e48c7f8a-4f53-4ee9-af26-6501b798f2af)

# Difference Between Linear And Logistic Regression


![image](https://github.com/Rohitbachchhe17/Logistic-_-regression-/assets/163370274/825fbde0-9cbe-40d9-a44f-2faed4f53939)
