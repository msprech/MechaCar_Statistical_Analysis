# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG 

![lm summary](https://github.com/msprech/MechaCar_Statistical_Analysis/blob/55632a4b982bd467e3c3708618c9068d52a0edbf/Screen%20Shot%202021-12-16%20at%2010.42.12%20AM.png)

We used a linear regression model on the MechaCar dataset to analyze the relationship between a car's mpg and several other variables. The model showed that the vehicle length and ground clearance were both statistically likely to provide a non-random amount of variance to the mpg values in the dataset. 

As the p-value was 5.35e-11, there is evidence to reject the null hypothesis, which means that the slope of the linear model is not considered to be zero. Therefore it is likely that several of the variables, such as those stated above, do have an impact on the mpg value. 

The r-squared value is also .71, meaning that approximately 71% of the mpg values can be determined by the created model, which is an effective prediction model. 

## Summary Statistics on Suspension Coils 

![total summary](https://github.com/msprech/MechaCar_Statistical_Analysis/blob/d01fcb599d1be6bfb59c37fc500f0a8583e5d247/total-summary.png)

The summary statistics for all of the lots together shows that their total suspension coil variance is within the 100 pounds per square inch specifications at 62.3. However, the summary statistics for each lot alone shows that lot 3 exceeds this limit with a variance of 170.3, which lot 1 and 2 are much lower. Lot 3 is therefore both not meeting design specifications and vastly skewing the total variance. 

![lot summary](https://github.com/msprech/MechaCar_Statistical_Analysis/blob/d01fcb599d1be6bfb59c37fc500f0a8583e5d247/lot-summary.png)

## T-Tests on Suspension Coils 

![t-test](https://github.com/msprech/MechaCar_Statistical_Analysis/blob/ac7e436c6c9fd71d0911db3049bc376f65fffb04/t.test.png)

This t-test was used to calculate if there was a statistical difference between the mean of the PSI across all of the lots and the population mean of 1500 pounds per square inch. The p-value, at .06, is not low enough to support a statistical difference between the means, as the total mean of 1498.78 is comparable to 1500.

Both lot 1 and lot 2 are also statistically similar to the population mean with respective means of 1500 and 1500.2 as well as p-values higher than .05. 

![lot 1](https://github.com/msprech/MechaCar_Statistical_Analysis/blob/ac7e436c6c9fd71d0911db3049bc376f65fffb04/t.test%20lot1.png) ![lot 2](https://github.com/msprech/MechaCar_Statistical_Analysis/blob/ac7e436c6c9fd71d0911db3049bc376f65fffb04/t.test%20lot2.png)

However, lot 3 has a p-value lower than the significance level at .041 and a mean of 1496.14. 

![lot 3](https://github.com/msprech/MechaCar_Statistical_Analysis/blob/ac7e436c6c9fd71d0911db3049bc376f65fffb04/t.test%20lot3.png)

## Study Design: MechaCar vs Competition 
