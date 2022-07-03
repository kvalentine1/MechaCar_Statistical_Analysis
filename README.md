# MechaCar_Statistical_Analysis

The purpose of this analysis is to analyze vehicle production metrics with linear regression models and t-tests.

## Linear Regression to Predict MPG

Three coefficients provided a non-random amount of variance to the mpg based on the linear regression model. These coefficients are vehicle length, ground clearance, and mpg (the intercept). 

The slope of the linear model would not be considered zero. The p-value of 5.35e-11 is smaller than the assumed significance level of 0.05. Therefore, the null hypothesis would be rejected indicating this is a non-zero slope.

The linear model does predict the mpg of the MechaCar effectively. The r-squared value is 0.7149 which indicates that this model will effectively predict 71% of mpg predictions.

## Summary Statistics on Suspension Coils

The MechaCar suspension coils design specifications dictate that the suspension coils must not exceed 100 pounds per square inch. The three lots total have a combined variance of 62.3 which is within design specifications. Individually, Lots 1 and 2 are within design specifications but Lot 3 exceeds the specifications with a variance of 170.3.

## T-Tests on Suspension Coils

The t-test of all lots indicates that the PSI among all lots is not statistically different from the population mean as indicated by the p-value of 0.603.

The t-test of Lot1 indicates that the PSI of Lot 1 is not statistically different from the population mean as indicated by the p-value of 1.

The t-test of Lot1 indicates that the PSI of Lot 2 is not statistically different from the population mean as indicated by the p-value of 0.61.

The t-test of Lot1 indicates that the PSI of Lot 3 is slightly statistically different from the population mean as indicated by the p-value of 0.042.

## Study Design: MechaCar vs Competition

For MechaCar to compare their vehicles to the competition’s, other metrics should be gathered. Given the data we already have, by obtaining data regarding city and highway MPG, towing capacity, and horsepower, we could conduct an analysis regarding how MechaCar vehicles compare to competitors in appealing to performance car enthusiasts and consumers who need significant hauling and offroad power. 
For this test, the data we could use is MPG, vehicle weight, and AWD. We would also need to obtain data for towing capacity, carrying capacity, and horsepower. A question we could pose is do MechaCar vehicles have similar MPG to competitor vehicles that have similar towing/carrying capacities and horsepower?

Our null hypothesis would be that MechaCar vehicles have similar MPG to competitor vehicles with similar performance.
Our alternate hypothesis is that MechaCar vehicles have better or worse MPG than competitor vehicles with similar performance. 

To evaluate this data we would use linear regression and t-test statistical tests.
![image](https://user-images.githubusercontent.com/101373173/177052063-428aea1a-6066-4055-8656-260197556d65.png)
