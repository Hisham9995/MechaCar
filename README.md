#   MechaCar_Statistical_Analysis


# Project Overview

This project is about analyzing metrics can  impact manufacturing a new car prototype  and compare vehicle performance ,The project involves the use of statistics and hypothesis testing to analyze a series of datasets from the automotive industry the comparsion including different factors such as   vehicle length, weight, spoiler angle, ground clearance, AWD capabilities, MPG, and PSI


# Linear Regression to Predict MPG




![linear_regression_summary PNG](https://user-images.githubusercontent.com/82621077/128645809-ab470c41-3060-4c22-9568-d2a9e6efd934.png)


In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results vehicle length and ground clearance (and Intercept) provide a non-random amount of variance to the linear model of mpg. At a significance level of 0.05, we are able to reject the null hypothesis because of the extremely small p-value. 
The null hypothesis of a linear regression explains  that the slope (β1) is  equal to 0 , if we reject the null hypthesis, we're stating that alternative (β1 ≠ 0)  proving that the slope is not 0.
Multiple R-squared increases as more variables are passed through the regression. However, adjusted R-squared controls against this increase, and adds penalties for the number of predictors in the model, a more accurate of how effective the linear model is. An adjusted R-square of 0.6825 concludes that this linear model predicts the mpg of MechaCar prototypes relatively well.


  
## Summary Statistics on Suspension Coils






![total_summary_table PNG](https://user-images.githubusercontent.com/82621077/128645881-4706d329-bbcc-47d3-9b3a-4eb2f4e374a6.png)
![lot_summary_table PNG](https://user-images.githubusercontent.com/82621077/128645889-aa083548-7f90-47e4-939e-079a20ddf2c4.png)




The design specifications for the MechaCar suspension coil in  the  dataset indicates that that the variance of the suspension coils must not exceed 100 pounds per square inch .  when we separated into three lots, the third lot demonstrates a much higher variance. , there is a possiblity that a third of the lot does not meet the necessary suspension coils requirement. Note that  lots are chosen randomly ,The Lot 3 is out of specs with a variance of 170.3 psi


# T-Test on Suspension Coils




![lots_t_test PNG](https://user-images.githubusercontent.com/82621077/128646004-4f7c87a0-ae12-4d9e-a815-fdefcf4b8948.png)



First of all   At a significance level of 0.05, we fail to reject the null hypothesis since the p-value equals 0.06.  we cannot reject the fact that the sample mean may be equivalent to the true population mean. Another feature to note is the narrow confidence interval. Although a narrower confidence interval mostly provides accurate than a wider interval 


1- __lot no 1__ Here the p-value is below the significance level of 0.05 percent, so we can reject the null hypothesis and conclude that the PSI across the Lot 1 is statistically different from the population mean.
 
2-__lot no 2__ At a significance level of 0.05, we fail to reject the null hypthesis again since the p-value equals 0.6072. The second lot also has a relatively small confidence interval.

3- __lot no 3__  the significance level of 0.05, we can reject the null hypothesis since the p-value equals 0.04168. we can not predict the population mean  in lot no 3


# Study Design: MechaCar vs Competition


To compare the performance of the MechaCar prototype against the vehicles from the competition, we will perform a statistical analysis  linear regression on city and highway fuel efficiency. (Gasoline), and it is an important feature that many consumers look at when purchasing a new car. based on the following metrics:

1) __Fuel efficiency (City and highway) MPG__
2) __Horse power: 0 to 60 mph" time__
3) __Vehicle weight__
4) __The safety rating__
5) __AWD capabilities__

The null hypothesis would be: each performance metrics is statistically similar between the MechaCar prototype and all vehicle from the other manufacturers.
We would use a one-way ANOVA test. To check if the mean of two or more groups are significantly different from each other.
So in this analysis we would compare the mean for each metric across the different manufacturers.

In order To perform the test, We need a data of MechaCar vehicles and its competition 
