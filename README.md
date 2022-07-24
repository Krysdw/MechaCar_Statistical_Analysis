# MechaCar_Statistical_Analysis
Written Summary

##Linear Regression to Predict MPG
Deliverable 1:
![image](https://user-images.githubusercontent.com/102800315/180666060-b607ab97-029d-4132-b2bb-b5d7fac304a8.png)

 

Regression Summary
In the regression model above, the Intercept, vehicle length and ground clearance all provide a non – random amount of variance to the mpg values in the dataset
The slope of the linear model is not considered to be zero because of the varied significance levels of multiple variables. Thus, a positive slope was generated. 
The linear model appears to predict the mpg of MechaCar prototypes effectively by way of generated R squared value of 71%, determined by all coefficients including: the vehicle weight, length, spoiler angle, and ground clearance. 


## Summary Statistics on Suspension Coils

Total_summary dataframe

![image](https://user-images.githubusercontent.com/102800315/180666095-edae6279-e3fb-46c8-8a85-dd510ff2fc04.png)




 

Lot Summary
 

![image](https://user-images.githubusercontent.com/102800315/180666107-e65b3a8b-d129-40c4-8832-5cdf553270b8.png)





Statistics on Suspension Coils Summary
The current manufacturing data doesn’t meet the overall design specifications for all manufacturing lots. At first glance of the total summary, specifications of the variance are met; total variance being about 62.3. However, when looking at the individual lot summaries, Lots 1 &2 come in meeting design specification, but Lot3 exceeds the variance of 100. 



## T – Tests on Suspension Coils


![image](https://user-images.githubusercontent.com/102800315/180666116-68bae71a-19b6-4273-90ae-c75cea30707e.png)



 

In Lot 1 the P-value of  0.00000156 is above significance level with no evidence to reject the null hypothesis. The PSI in general is statistically similar to the mean of 1500 psi.

 
 
 ![image](https://user-images.githubusercontent.com/102800315/180666123-a0f8d880-7b88-40c7-830f-dc67bfec519b.png)

 
 
 
 

In Lot2 our p-value is 0.000591 and below the significance threshold. PSI at lot 2 is not statistically similar to the population mean of 1498.78

 
 ![image](https://user-images.githubusercontent.com/102800315/180666146-da75d211-40f7-41a6-a0a5-b9f41dc4bef3.png)

 
 
 
 

In Lot3 our p-value is .159. We can state that the PSI at lot 3 is statistically similar to the population mean of 1496 psi.
## Study Design: MechaCar vs Competition
Outside of popularity and the psychology that comes with choosing vehicles to purchase, there are defined metrics that decide the value and thus competitive ability of a vehicle. Those metrics being cost, miles per gallon, interior and exterior features, space, and safety to name a few. A similar regression model including the above metrics and compared to the MechaCar metrics. The value will be determined by the consumer needs ie cost, style, space, safety. 

Metrics
In the regression model, the cost of the vehicle would be compared to mpg, number of features, sq footage and safety rating.

Null or Alt Hypothesis
The null hypothesis would be that the 4 metrics have no statistical significance on the cost of the vehicle. 

Statistical Test
A linear regression test combining all variables: mpg, square footage, safety rating, and features compared to the average vehicle cost. 

Data need for Statistical Test
The data needed to run the proposed statistical test would be the following specs of MechaCar and  of the competition; cost, mpg, space (sq. ft), features, and safety rating. 
