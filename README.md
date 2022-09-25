# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG

![linear regression](https://user-images.githubusercontent.com/105949411/192162191-ab1f3d54-9b83-4247-adf6-ea08fa9caf59.png)

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The variables that provided a non-random amount of variance to the mpg values in the dataset of the MechaCar were the Vehicle Length and the Ground Clearance.

2. Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model can't be considered to be zero; as the p-value of 5.35x10-11 is lower than even an extreme level of significance. So the null hypothesis must be rejected. This means that the relationship between our variables and the miles per gallon is subject to more than random chance.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

This linear model has an r-squared value of 0.7149. This means that approximately 71% of all mpg predictions will be determined by this model. Therfore this multiple regression model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils

![total summary](https://user-images.githubusercontent.com/105949411/192165140-1537221f-0dee-4430-a5f7-3762a1098ff2.png)

![lot summary](https://user-images.githubusercontent.com/105949411/192165144-6f649d7f-7553-4bf7-9c94-d8700465380f.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The overall Variance as shown in the Total Summary is under 100 psi. However, there is a problem with Lot 3. As shown in the Lot Summary the variance for Lot 3 is well above the acceptable threshold of 100 at 170.28.

## T-Tests on Suspension Coils

![t test](https://user-images.githubusercontent.com/105949411/192166428-66c54513-a2b9-4365-8abf-2fb998a3a720.png)

The t-test run over the suspension coils across all the manufacturing lots shows they are not statistically different from the population mean. The p-value is not low enough to reject the null hypothesis.

![t test lo 1](https://user-images.githubusercontent.com/105949411/192166435-fa9e0b48-5ee2-4d1e-84bb-5e85bfc14a9b.png)

The results of the T-test for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough to reject the null hypothesis.

![t test lot 2](https://user-images.githubusercontent.com/105949411/192166443-950c449c-d5bf-43f7-8bd5-3da63bcd97d3.png)

The results of the T-test for Lot 2 shows that they are not statistically different from the population mean. The p-value is not low enough to reject the null hypothesis.

![t test lot 3](https://user-images.githubusercontent.com/105949411/192166450-f97a45ce-8f4b-47f5-88e8-fe42a1ad0f8f.png)

The results of the T-test for Lot 3 shows that they are slightly statistically different from the population mean. The p-value is low enough for us to reject the null hypothesis. This lot may be need to be discarded.

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

With gas prices continuing to rise and showing no signs of dropping I believe consumers will be most interested in fuel efficiency, cost of the vehicle and repair cost.

What metric or metrics are you going to test?

The metrics we will test are highway and city fuel efficiency, cost of the vehicle, and average repair costs.

What is the null hypothesis or alternative hypothesis?

Null Hypothesis (Ho): MechaCar is priced correctly based on its metrics when compared to similar vehicles.

Alternative Hypothesis (Ha): MechaCar is not priced correctly based on its metrics when compared to similar vehicles.

What statistical test would you use to test the hypothesis? And why?

I would use a multilinear regression to test multiple independent variables.

What data is needed to run the statistical test?

We would need gather highway and city fuel efficiency, cost of the vehicle, and average repair costs from both MechaCar data and its competitors.

