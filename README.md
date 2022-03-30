# MechaCar_Statistical_Analysis
## OVERVIEW:
- This analysis will look into the performance statistics of the MechaCar.
## Results:
### Linear Regression to Predict MPG:
![Deliverable1](https://user-images.githubusercontent.com/93515126/160767577-de76279d-8f7e-4a6f-b81b-9915ba9db227.png)
- From the data, We can see that the vehicle length and ground clearance are statistically significant and provide the model a lot of variety. Weight, spoiler angle, and AWD all have large p-values, implying that these are random variations.
- With an r-square of 0.68, we may infer that the mpg can be anticipated about (68%) of the time.
### Summary Statistics on Suspension Coils:
![Total_Suspension_Coil](https://user-images.githubusercontent.com/93515126/160768143-63e525e9-6d77-4b6b-88af-40216bb38b33.png)
![Suspension_Coils_by_Lots](https://user-images.githubusercontent.com/93515126/160768173-697ac050-d953-459a-b9bc-04a20d34c7d6.png)
- The overall variation for the Total Summary data is less than 100 psi, but the variance for Lot3 (170) indicates a possible outlier for the data.
### T-Tests on Suspension Coils:
![Deliverable3](https://user-images.githubusercontent.com/93515126/160768666-293bebb8-dcdf-455e-b4a3-c36e10ef5f69.png)
- The t-test reveals that the p-values for Lots 1 and 2 are insufficient to reject the null hypothesis, however for Lot 3, a p-value of 0.04 might be sufficient to reject the null hypothesis.
### Study Design: MechaCar vs Market Competition:
- The next investigation should focus on the cars' dependability.
- New hypothesis: The MechaCar's maintenance costs are a factor in its overall pricing.
#### New Metric Test
- The maintenance cost of ownership for the vehicle.
#### Null Hypothesis
After identifying which aspects are critical to the genre of the MechaCar:
- Null Hypothesis (Ho): MechaCar is properly priced based on its performance in key genre parameters.
- Alternative Hypothesis (Ha): MechaCar's pricing is incorrectly set based on its genre's key performance indicators.
#### Statistical Tests
- To establish which components have the strongest correlation/predictability with the list selling price (dependent variable), a multiple linear regression would be used; which combination has the largest influence on price, a multiple linear regression would be used.
#### Data That Needs Collecting
-The cost of each repair or maintenance bill.

