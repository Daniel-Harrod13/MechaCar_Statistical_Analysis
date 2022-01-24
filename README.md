# MechaCar_Statistical_Analysis
## Project Overview
In this project, we used R. to analyze production data for AutoRUs's newest vehicle prototype MechaCars. The prodution team has asked us to analyze perfromance of the prototype across all of their manufacturing lots. The metrics of the vehicle we analyzed were the Vehicle Length, weight, spoiler angle, ground clearance, AW capabilites, MPG, and PSI.
## Linear Regression for MPG prediction
1. Varience to determine a non-random variable is amost often 0. Due to this, we can see that intercept, vehicle_length, amd ground clearance, coeeffcients are proven to be a non-random amount of variance in regards to miles per gallon or mpg.
2. At this time we can reject the null hypothesis because of the value size of the p-value. Null hypothesis states that slope is equal to 0. since we are rejecting the nulll hypothesis, we are stating that the slope is not equal to zero.
3. R-squared is known to increase that more varaibles are moved or placed in the regression. However, when we adjust the r-squard agasint the increase, penalties are added for the predicotrs in the model, thus creating a more accurate predictions on the effectiveness of the linear model. The adjusted R-square of 0.6825 shows us that this model can accurately predict the MPG of the vehicle protoype in a reltively well manner.

## Summary of Suspension Coil
The varience totals found for the data on suspension coils shows that the manufacturing data reachs the limitation at the adequate level of 100 lbs per square inch. When seperated into the three Manufacturting Lots however, we see that lot three has a much higher varience at  
