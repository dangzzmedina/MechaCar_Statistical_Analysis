# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
**The p-value in Vehicle_Length and ground_clearance have a probability value below our assumed 0.05% significance level making it significant a less non-random variant.


Is the slope of the linear model considered to be zero? Why or why not?
** we can state that there is sufficient evidence to reject our null hypothesis because the p-value is smaller than our significance level of 0.05% making our slope of our linear model not zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Our Multiple R-Square value is 0.7149 in other words 71.49% of the variability of our dependent variables which makes our linear model prediction more accurate than innacurate.

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The variance in Lot 1 and Lot 2 are less than 100 which means they do have the design specification. But, to answer the question, not all manufacturing lots can meet criteria (Lot 3 does not). In the other hand, when you do not divide "Lots", we get less than 100 as well.


## Study Design: MechaCar vs Competition.

What metric or metrics are you going to test? highway fuel efficiency vs horsepower

What is the null hypothesis or alternative hypothesis? The null hypothesis is between knowing both mechaCar vs Competition cars have same fuel efficiency when horsepower increases. Otherwise we use an alternative if the statistical analysis come out as distinct.

What statistical test would you use to test the hypothesis? And why? I would test the multi regression model with the different car classes and see their performance to measure the p-value in the different classes to look for a significance level that will answer our analysis.

What data is needed to run the statistical test? To divide classes with an equal distribution and same dependent variables of at least 2.
