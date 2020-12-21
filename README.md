# MechaCar_Statistical_Analysis
The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance were analyzed to determine if the factors have a significant impact on miles per gallon.

## Deliverable 1: Linear Regression to Predict MPG
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Is the slope of the linear model considered to be zero?
Does this linear model predict mpg of MechaCar prototypes effectively?

![Linear_regression](https://user-images.githubusercontent.com/69759624/102735097-26387b80-4307-11eb-8ca5-a8e64d024539.PNG)

Overall, the p-value is 5.35x10E-11 and this number is less than the significance value of 0.05. We reject the null hypothesis and state there's a correlation between the car factors and mile per gallon. The factors that provide a non-random amount of variance to the mpg values are car weight, spoiler angle, and drivetrain (i.e. AWD) because the individual p-values are greater than the significance level of 0.05 and have values of 0.0776, .3069, and .1852, respectively.

The slope of the linear model is not zero and we reject the null hypothesis. We accept the alternative hypothesis and state that the slope is a non-zero value.

The r-squared value is 0.7149 which shows the linear model does predict mpg of the MechaCar prototypes effectively. The mpg is dependent on the car weight, spoiler angle, and drivetrain.

## Deliverable 2: Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually?

### Design specification requirement for all the manufacturing lots and each lot individually
The overall variance for the three combined lots is less than 100 PSI with a value of 62.29 PSI. This result meets the design specification.
![Total_summary](https://user-images.githubusercontent.com/69759624/102734267-0d2ecb00-4305-11eb-90f1-97bef5d1af11.PNG)

The variances for LOT 1 and LOT 2 are also less than 100 PSI at 0.98 and 7.47 PSI, respectively, and both lots meet the design specification. Only the variance for LOT 3 is greater than 100 PSI with a value of 170.29 PSI, and LOT 3 does not meet the design specification.
![Lot_summary](https://user-images.githubusercontent.com/69759624/102734707-1cfadf00-4306-11eb-9173-9bf9b7f03433.PNG)

## Deliverable 3: T-Test on Suspension Coils
Four t-tests were completed for 1) all manufacturing lots combined, 2) manufacturing LOT 1, 3) manufacturing LOT 2, and 4) manufacturing LOT 3 to compare each manufacturing lot against the mean PSI of the population (1500 PSI).

![image](https://user-images.githubusercontent.com/69759624/102735639-9398dc00-4308-11eb-960a-ee0ef12908c1.png)

The summary of the t-test results showed that the null hypothesis is accepted for the t-test for all manufacturing lots combined, LOT 1, and LOT 2 because the p-values are greater than 0.05. The null hypothesis states that there is no statistical difference between the lot tested and the mean PSI of 1500.

The null hypothesis is rejected for LOT 3 because the p-value of 0.042 is less than the significance level of 0.05.

## Deliverable 4: Study Design: MechaCar versus Competition
### A metric to be tested is mentioned
### A null hypothesis or an alternative hypothesis is described
### A statistical test is described to test the hypothesis
### The data for the statistical test is described
