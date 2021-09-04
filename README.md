# Random-Forest-Algorithm-Machine-Learning

## The Random forest classifier 
is the group of decision tree 
In random forest will divide our dataset into small datasets for decision trees 
Here some features may replicate
## Bootstrap 
is a technique in row sampling and column sampling occur and we will give that data into decision tree 
The random forest work on majority voting which is known as aggregation.
## Majority voting
means that that result will be select which comes more time 
## Bagging Technique 
The combination of bootstrap and Aggregation is called bagging 
Bagging = bootstrap + aggregation
Random forest Algorithm is Ensemble Method.it is collects the prediction from multiple decision trees
## Ensemble Method 
is a technique in which predictions from multiple machine learning algorithms combine together to make more prediction 
## Disadvantages of Decision tree 
Low bas  : good result on training data
High variance : bad result in testing data 
The problem will come with overfitting 
In Random forest we do some feature Scaling 
Feature Scaling
## Feature Scaling
is a technique to standardize the independent features present in the data in a fixed range. It is performed during the data pre-processing to handle highly varying magnitudes or values or units. If feature scaling is not done, then a machine learning algorithm tends to weigh greater values, higher and consider smaller values as the lower values, regardless of the unit of the values.
Example: If an algorithm is not using the feature scaling method then it can consider the value 3000 meters to be greater than 5 km but that’s actually not true and in this case, the algorithm will give wrong predictions. So, we use Feature Scaling to bring all values to the same magnitudes and thus, tackle this issue.

#### Standardization and Normalization
### 1
### Normalization  
Normalization is a scaling technique in which values are shifted and rescaled so that they end up ranging between 0 and 1. It is also known as Min-Max scaling.
### 2
#### Standardization 
is another scaling technique where the values are centered around the mean with a unit standard deviation. This means that the mean of the attribute becomes zero and the resultant distribution has a unit standard deviation. (ie) in which mean is 0 and standard devation is 1.
The standard deviation is a statistic that measures the dispersion of a dataset relative to its mean. It is calculated as the square root of variance 
