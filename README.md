# MechaCar_Statistical_Analysis
The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance were analyzed to determine if the factors have a significant impact on miles per gallon.

## Deliverable 1: Linear Regression to Predict MPG
write a short summary using a screenshot of the output from the linear regression, and address the following questions:

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Is the slope of the linear model considered to be zero?
Does this linear model predict mpg of MechaCar prototypes effectively?

Overall, the p-value is 5.35x10E-11 and this number is less than the significance value of 0.05. We reject the null hypothesis and state there's a correlation between the car factors and mile per gallon. The factors that provide a non-random amount of variance to the mpg values are car weight, spoiler angle, and drivetrain (i.e. AWD).

The slope of the linear model is not zero and we reject the null hypothesis. We accept the alternative hypothesis and state that the slope is a non-zero value.

The r-squared value is 0.7149 which shows the linear model does predict mpg of the MechaCar prototypes effectively.

## Deliverable 2: Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually?

### Design specification requirement for all the manufacturing lots and each lot individually
The overall variance for the three combined lots is less than 100 PSI with a value of 62.29 PSI.
![Total_summary](https://user-images.githubusercontent.com/69759624/102734267-0d2ecb00-4305-11eb-90f1-97bef5d1af11.PNG)

The variances for LOT 1 and LOT 2 are also less than 100 PSI at 0.98 and 7.47 PSI, respectively. Only the variance for LOT 3 is greater than 100 PSI with a value of 170.29 PSI.
![Lot_summary](https://user-images.githubusercontent.com/69759624/102734707-1cfadf00-4306-11eb-9173-9bf9b7f03433.PNG)

## Deliverable 3: T-Test on Suspension Coils
An RScript is written for three t-tests that compare each manufacturing lot against mean PSI of the population (10 pt)
There is a summary of the t-test results across all manufacturing lots and for each lot 

briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary

Overall, accept null hypothesis
LOT 1 accept null
LOT 2 accept null
LOT 3 reject null because p<0.05

## Deliverable 4: Design a Study Comparing the MechaCar to the Competition
### A metric to be tested is mentioned
### A null hypothesis or an alternative hypothesis is described
### A statistical test is described to test the hypothesis
### The data for the statistical test is described
