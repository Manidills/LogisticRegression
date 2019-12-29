# LogisticRegression
LogisticRegression with feature Selection

Find the relationship between features and prob of particular outcome. Similar to the linear regression, but here it use the sigmoid function shape with average thershold using maximum likelihood to find the best fit.

sigmoid=1/1+e^-z

metrics= Accuracy

Code-

1. load titanic dataset
2. remove the null values and high null value column
3. Find the correlation between data
4. Try with RFE to select the features number { feature selction }
5. fit the model
6. calulate the metrics


Basically, LR is used to predict the values in binary outcomes 
