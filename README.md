# MechaCar Statistical Analysis
The following report is our analysis on the production data from the manufacturing team at MechaCar

## Linear Regression to Predict MPG
Below please find a chart of our finding for the Linear Regression that predicts MPG.

![Linear.png](Images/Linear.png) 

Our research discovered that ground clearance and vehicle length gives us the best options for most fuel efficiency. Both of these variables showed a non-random amount of variance to the mpg values in the dataset.

The slope of the linear model is not considered to be zero because it's below the p-value.

This linear model predicts mpg of MechaCar prototypes effectively because it has a 71% predicatablitily that the mpg values will be correctly acheived.  

## Summary Statistics on Suspension Coils
Below are two charts the give a total summary (top) of all lots and a lot summary (bottom) of each lot.

![total_summary.png](Images/total_summary.png)
![lot_summary.png](Images/lot_summary.png)

It is our findings that the current manufacturing data meets the design specification for all manufacturing lots. The variance is 62.29% with a standard deviation of 7.89 
However, each lot individually does not meet the design specifications. Lots 1 and 2 are within tolerance with a variance of 0.97 for lot 1 and 7.46 for lot 2. Lot 3 has a variance of 170.28. This is completely unexcetable. 

## T-Tests on Suspecsion Coils
![All_T_test.png](Images/All_T_test.png)
![Lot1_T_test.png](Images/Lot1_T_test.png)
![Lot2_T_test.png](Images/Lot2_T_test.png)
![Lot3_T_test.png](Images/Lot3_T_test.png)
