# Regression

## Linear Regression

### Dataset
The adverstiting dataset captures sales revenue generated with respect to advertisement spends across multiple channles like radio, tv and newspaper.

### Objective
The objective is to use linear regression to understand how advertisement spending impacts sales.

### Solution
I start off first by considering only the effect of TV ads on sales. A single linear regression model is built for this which gives an R^2 of 0.61.
Next, I built a multiple linear regression model considerung the effect of TV and radio ads on sales. This increased the R^2 to 0.89.
Finally, I check the interaction between TV and radio and consider that in the model. This helps increase the R^2 to 0.97 and brings the RMSE to 0.7.

## Logistic Regression

### Dataset
The dataset being used is the Breast cancer classification dataset.

### Objective
The objective is to classify if a breast cancer diagnosis is malign or benign.

### Solution
I started off first by logistic regression and then also built a classifier with LDA and another classifier with QDA.
The performance of the model is evaluated using ROC curve and by finding Area Under the Curve (AUC). LDA method gave the best result with AUC = 0.99
