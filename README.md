#   MechaCar_Statistical_Analysis


# Project Overview

This project is about analyzing metrics can  impact manufacturing a new car prototype  and compare vehicle performance ,The project involves the use of statistics and hypothesis testing to analyze a series of datasets from the automotive industry the comparsion including different factors such as   vehicle length, weight, spoiler angle, ground clearance, AWD capabilities, MPG, and PSI


# Linear Regression to Predict MPG






![linear_regression PNG](https://user-images.githubusercontent.com/82621077/128645603-81770b52-b17e-4ba7-a468-11a915d93999.png)

__Call:
lm(formula = mpg ~ vehicle_length + vehicle_weight + spoiler_angle + 
    ground_clearance + AWD, data = mecha_car_mpg)__

__Coefficients:
     (Intercept)    vehicle_length    vehicle_weight     spoiler_angle  ground_clearance               AWD  
      -1.040e+02         6.267e+00         1.245e-03         6.877e-02         3.546e+00        -3.411e+00__  
