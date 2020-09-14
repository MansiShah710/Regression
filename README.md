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
