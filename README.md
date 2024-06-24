# AI Trainee - Week_3

## Linear Regression Exploration

1. Simple linear regression
2. Loss function: MSE, MAE
3. Manual backpropagation
4. Built and Trained the model

# ----------------------------------------------------------

# Assignment

Dataset: `Housing.csv`

## Objective

To predict the price of houses based on the given features.

## Work Flow:

1. Performed Exploratory Data Analysis
2. Handled the skewness and outliers from the features: `price` and `area`.
3. Used Log transformation to handle skewness.
4. Analyzed categorical features and perform nominal encoding on them except for `furnishingstatus`.
5. For `furnishingstatus`, checked out ordinal as well as one-hot encoding to see what gives better result.
6. Analyzed Correlation plots and dropped some features having low correlation with the target. -- `hotwaterheating`.
7. Checked if independent features are also corelated or not. Found some. But dropping them didn't improve the overall result.\
8. Split the dataset into train and test set and also scale the data.
9. Built Linear Regression Model.
10. Used `MSE`,`MAE` and `Log(cosh(x))` as the cost function.
11. Trained the model on each one of them.
12. Used R2 score as the evaluation metric.

## Output:

`Training Set : 0.6921`
`Test Set : 0.6837`
