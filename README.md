#   MechaCar_Statistical_Analysis


# Project Overview

This project is about analyzing metrics can  impact manufacturing a new car prototype  and compare vehicle performance ,The project involves the use of statistics and hypothesis testing to analyze a series of datasets from the automotive industry the comparsion including different factors such as   vehicle length, weight, spoiler angle, ground clearance, AWD capabilities, MPG, and PSI


# Linear Regression to Predict MPG




![linear_regression_summary PNG](https://user-images.githubusercontent.com/82621077/128645809-ab470c41-3060-4c22-9568-d2a9e6efd934.png)


In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results vehicle length and ground clearance (and Intercept) provide a non-random amount of variance to the linear model of mpg. At a significance level of 0.05, we are able to reject the null hypothesis because of the extremely small p-value. 
The null hypothesis of a linear regression explains  that the slope (β1) is  equal to 0 . However, if we reject the null hypthesis, we're stating that alternative (β1 ≠ 0)  proving that the slope is not 0.
Multiple R-squared increases as more variables are passed through the regression. However, adjusted R-squared controls against this increase, and adds penalties for the number of predictors in the model, a more accurate of how effective the linear model is. An adjusted R-square of 0.6825 concludes that this linear model predicts the mpg of MechaCar prototypes relatively well.


  
## Summary Statistics on Suspension Coils






![total_summary_table PNG](https://user-images.githubusercontent.com/82621077/128645881-4706d329-bbcc-47d3-9b3a-4eb2f4e374a6.png)
![lot_summary_table PNG](https://user-images.githubusercontent.com/82621077/128645889-aa083548-7f90-47e4-939e-079a20ddf2c4.png)
