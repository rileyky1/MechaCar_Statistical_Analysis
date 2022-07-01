# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

According to the summary output of the multiple linear regression model, vehicle length and ground clearance (and intercept) are statistically unlikely to provide random amounts of variance. They have a significant impact on the miles per gallon (mpg) values in the dataset.

The slope of the linear model is not considered to be zero because there is a significant linear relationship. Additionally, the p-value of our linear regression analysis is smaller than the assumed significance level of 0.05%. This indicates that there is sufficient evidence to reject the null hypothesis and confirm that the slope is not zero.

The linear model predicts mpg of MechaCar prototypes effectively as evidenced by a r-squared value of 0.71, indicating a strong correlation of the dataset.

![linearregression](linearregression.png)

## Summary Statistics on Suspension Coils

Summary statistics were generated in order to compare any suspension coil production differences between each of the manufacturing plants at MechaCar. Design specifications dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

Based on the current pounds per square inch (PSI) data for all three manufacturing lots, the total variance is acceptable at 62.29 PSI. 

![total_summary](total_summary.png)

Lot1 and Lot2 both have acceptable variance of 0.98 PSI and 7.47 PSI, respectfully. However, when analyzng each manufacturing lot individually the data shows that the variance for Lot3 is unacceptable as evidenced by a variance of 170.29 PSI.

![lot_summary](lot_summary.png)