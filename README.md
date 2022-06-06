# MechaCar_Statistical_Analysis
# Deliverable 1
## Linear Regression to Predict MPG

1. The vehicle length and vehicle ground clearance are the most statistically significant to provide amounts that are non-random for the model variance. Meaning, vehicle length and ground clearance will have a significant impact on the miles per gallon (MPG) MechaCar prototype. The vehicle weight, spoiler angle, and All Wheel Drive (AWD) have a random amount of variance with the dataset due to the p-values. 
2. For this model the p-value: 5.35e-11, is well below the significance level of .05%. This means that there is enough evidence to reject our null hypothesis. Which provides further evidence that the slope of this linear model is not equal to zero.
3. The r-squared value is .7149 which means that 71.49% of the MPG predictions can be determined by the model. What this provides is insight into the MechCar prototypes that we will be unable to predict MPG using this model.

![ Deliverable 1 Picture 1](https://github.com/gonzalesbarrett/MechaCar_Statistical_Analysis/blob/main/Images/Deliv1_1.jpg)

![ Deliverable 1 Picture 2](https://github.com/gonzalesbarrett/MechaCar_Statistical_Analysis/blob/main/Images/Deliv1_2.jpg)


# Deliverable 2

## Summary Statistics on Suspension Coils

Once the Suspension_Coil.csv was converted into a data frame we created two subset tables along with it which were Total summary and Lot Summary. For Total Summary, we are looking at the PSI statistics across all of the lots. The Lot Summary tells us the statistics of each lot (screenshot below). The findings were that Lot 1 and Lot 2 share several similarities. On the other hand, lot 3 has a much smaller mean with a larger variance and standard deviation.

![Deliverable 2 Picture 1](https://github.com/gonzalesbarrett/MechaCar_Statistical_Analysis/blob/main/Images/Deliv2_1.jpg)

![ Deliverable 2 Picture 2](https://github.com/gonzalesbarrett/MechaCar_Statistical_Analysis/blob/main/Images/Deliv2_2.jpg)

# Deliverable 3

## T-Tests on Suspension Coil

The T-test for the suspension coils for all of the manufacturing lots tells us that they are not statistically different from the population mean. The p-value is .0603 which is not low enough for us to reject the null hypothesis.

For Lot 1, shows us that they are not statistically different from the mean population and the 1 p-value is not low enough to reject the null hypothesis. 

Lot 2 has the same conclusion of Lot 1 with a p-value of .6702.

Lot 3 tell us that they are slightly statistically different from the mean population with a p-value of .0417 we can also reject the null hypothesis. 

![ Deliverable 3 Picture 1](https://github.com/gonzalesbarrett/MechaCar_Statistical_Analysis/blob/main/Images/Deliv3_1.jpg)

# Deliverable 4

## Study Design: MechaCar vs Competition

When deciding to purchase a vehicle many factors must be considered. The requirements of a vehicle vary greatly from person to person but generally speaking, MPG is one of the first considerations. Based on our analysis, MPG is affected by car weight, AWD, and spoiler angle. For the MechaCar, all of these things would need to be considered. We were able to determine that Lot 3 would most likely not be a good fit due to the variances and lower PSI average.

- What metric or metrics are you going to test?

Safety feature rating, cost, drive package, engine type, depreciation, maintenance cost, and MPG. 

- What is the null hypothesis or alternative hypothesis?

Null Hypothesis: MechaCar is correctly priced when based on key factor performance for its genre.

Alternative Hypothesis: MechaCar is not priced correctly when based on key factor performance for its genre.

- What statistical test would you use to test the hypothesis? And why?/ What data is needed to run the statistical test?

I would use a multiple linear regression to determine the highest correlation and predictability with the listing price to show which pairing would have the largest impact on price. We would need to gather relevant data for prototypes and competitors to accurately compare. 

