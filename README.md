# MichaelOkoro24-MechaCar_Statistical_Analysis

## Linear Regression
![Screen Shot 2022-09-21 at 3 18 28 PM](https://user-images.githubusercontent.com/106411743/191591775-29912377-35e4-4d29-b30c-bedb3112e26b.png)

                                 #### Deliverable 1 #####
## Linear Regression to Predict MPG
![Screen Shot 2022-09-21 at 3 01 24 PM](https://user-images.githubusercontent.com/106411743/191589288-e938b422-9462-4982-bee3-8d3f438140ab.png)

## 1.Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Coefficients:
mpg: -1.040e+02 < .05, statistically significant, non-random amount of variance
vehicle length:  6.267e+00 > .05, statistically significant, non-random amount of variance
vehicle weight: 1.245e-03 < .05 not statistically significant, random amount of variance
spoiler angle:   6.877e-02 < .05 not statistically significant, random amount of variance
ground clearance: 3.546e+00  > .05 statistically significant, non-random amount of variance
AWD:   -3.411e+00 < .05 not statistically significant, random amount of variance

As shown only the vehicle weight and ground clearence have a non-random amount of variance applied to the mpg values.That is to say, the vehicle length and vehicle ground clearance have a significant impact on miles per gallon on the MechaCar prototype.


## 2.Is the slope of the linear model considered to be zero? Why or why not?
The p-value of our linear regression is 5.35e-11 which is below our significance level of 0.05. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.


## 3.Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The r-squared value is 0.7149 which means 71% of the mpg predictions will be determined by this model. Which is more than half so, this linear model does predict mpg of MechaCar prototypes effectively. 

## Summary Statistics on Suspension Coils
                                   ###### Deliverable2 ######

## Total Summary
![Screen Shot 2022-09-21 at 4 56 12 PM](https://user-images.githubusercontent.com/106411743/191608799-838ffc86-eabd-4181-9e9c-05265ea2cb6d.png)

## Lot Summary
![Screen Shot 2022-09-21 at 4 57 22 PM](https://user-images.githubusercontent.com/106411743/191608914-e9037c13-e6b5-4522-ab97-134462fce253.png)


1.The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The current manufacturing data for Lot 1 has a variance of 0.9795918 and the data for Lot 2 has a variance of 7.4693878 which is both below 100. However; Lot 3 has a variance of 170.2861224 which exceeds 100 pounds per square inch. 


                                    ###### Deliverable3 #######
## T-Tests on Suspension Coils
## T-Test for all Lots
![Screen Shot 2022-09-21 at 6 47 33 PM](https://user-images.githubusercontent.com/106411743/191623659-d08b071f-8494-46b1-a4ee-fc193235ef43.png)

The p-value for all the lots is 0.06 which is larger than our significance level of 0.05, which means we do not have sufficient evidence to reject our null hypothesis, and therefore we fail to reject our null hypothesis.


## T-Test for Lot 1
![Screen Shot 2022-09-21 at 6 55 31 PM](https://user-images.githubusercontent.com/106411743/191624402-0992dc40-15cf-4d9b-a4a2-ce03098b3f60.png)

The p-value for all Lot 1 is 1 which is larger than our significance level of 0.05, which means we do not have sufficient evidence to reject our null hypothesis, and therefore we fail to reject our null hypothesis.


## T-Test for Lot 2

![Screen Shot 2022-09-21 at 6 56 17 PM](https://user-images.githubusercontent.com/106411743/191624469-a6141fe8-2c10-4da1-b8ad-b93bbe3a5fcd.png)

The p-value for Lot 2 is 0.6072 which is larger than our significance level of 0.05, which means we do not have sufficient evidence to reject our null hypothesis, and therefore we fail to reject our null hypothesis.



## T-Test for Lot 3

![Screen Shot 2022-09-21 at 6 56 58 PM](https://user-images.githubusercontent.com/106411743/191624549-5b426aae-badb-427c-85ee-ad83dd398c25.png)

The p-value for Lot 3 is 0.04168 which is smaller than our significance level of 0.5, there is sufficient statistical evidence that our null hypothesis is not true, and therefore we would reject our null hypothesis.


                                       ###### Deliverable 4 #######

## Study Design: MechaCar vs Competition

Some metrics of the MechaCar that could be of interest to the user are cost, city or fuel efficiency, horse power, maintenance cost, engine type, or safety rating

## 1. What metric or metrics are you going to test?

The metric I would test would be fuel efficiency before and after oil change.

## 2. What is the null hypothesis or alternative hypothesis?

The null hypothesis is that the mean of the fuel efficiency will not change.
The alternative hypothesis is that mean of the fuel efficiency  will change.

## 3. What statistical test would you use to test the hypothesis? And why?

The statistical test I would use is a two sample t-Test to compare the samples of the fuel efficiency before and after the oil change. This will help us see if there is a major staistical difference in the datasets.

## 4. What data is needed to run the statistical test?

A random sample of about 50 for MechaCars and it's competitors with both of their fuel efficiency numbers before and afer an oil change.






