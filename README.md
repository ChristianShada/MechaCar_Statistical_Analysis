# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG<br><br>
### Deliverable 1
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?<br><br>
<img align="right" width="500" height="300" src=https://user-images.githubusercontent.com/89173945/149685366-5193a82d-75d7-48e3-89b9-5afcfde564e8.png>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Looking at the data to the right, we can come to the
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;conclusion that the ground clearance and the vehicle's
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;length and width provides the non-random variance
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;that contributes to the MPG in the dataset.<br><br>

* Is the slope of the linear model considered to be zero? Why or why not?<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The slope of the linear model is not considered to be 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;zero. The p-Value of 5.35e-11, is smaller than the level 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;of .05% which would reject the null hypothesis which 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;further suggests that the slope of this model is **not** 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;zero.<br><br>

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This linear model **does** predict the MPG of MechaCar prototpys effectly. As a result of the r=squared value of .7149 (about 71%), &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;of all predictions can be determined by this model.<br><br>

## Summary Statistics on Suspension Coils<br><br>
### Deliverable 2
* The suspension coil’s PSI continuous variable across all manufacturing lots.<br><br>
<img align="left" width="500" height="150" src=https://github.com/ChristianShada/MechaCar_Statistical_Analysis/blob/main/Resources/Total_Sumary.PNG><br><br><br><br><br><br><br><br>
* The following PSI metrics for each lot: mean, median, variance, and standard deviation.
<img align="left" width="700" height="150" src=https://github.com/ChristianShada/MechaCar_Statistical_Analysis/blob/main/Resources/Lot_Summary.PNG><br><br><br><br><br><br><br><br>
* Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Given that the suspension coils must not exceed 100 pounds PSI, as disctated by the designs for the MechaCars, the data shows 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;that the coils are well within the  the varience of the coils at 62.29. However when one looks at the lots individually, you will notice 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;that Lot3's varience is above the required PSI at 170.29 which causes the average of the lot Varience to be at 62.29. See the box 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;plot below as additional info.<br>
<img align="right" width="600" height="600" src=https://github.com/ChristianShada/MechaCar_Statistical_Analysis/blob/main/Resources/Box_Plot_IndividualLot.PNG><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## T-Tests on Suspension Coils<br><br>
### Deliverable 3
* An RScript is written for t-test that compares all manufacturing lots against mean PSI of the population<br><br>
<img align="left" width="500" height="200" src=https://user-images.githubusercontent.com/89173945/149690381-38270b42-94a5-48c8-a677-0fdc967ca8c0.png><br><br><br><br><br><br><br><br><br>
* An RScript is written for three t-tests that compare each manufacturing lot against mean PSI of the population<br><br>
<img align="left" width="500" height="200" src=https://user-images.githubusercontent.com/89173945/149690700-9f978f74-c360-4817-993d-b43b8f7e13b0.png><br><br><br><br><br><br><br><br><br>
_Lot 1 sample actually has the true sample mean of 1500, again as we saw in the summary statistics above. With a p-Value of 1, clearly we cannot reject (i.e. accept) the null hypothesis that there is no statistical difference between the observed sample mean and the presumed population mean (1500).<br><br>_
<img align="left" width="500" height="200" src=https://user-images.githubusercontent.com/89173945/149691259-c9368d7a-0a12-4413-acf3-804aa938f537.png><br><br><br><br><br><br><br><br><br>
_Lot 2 has essentially the same outcome with a sample mean of 1500.02, a p-Value of 0.61; the null hypothesis cannot be rejected, and the sample mean and the population mean of 1500 are statistically similar.<br><br>_
<img align="left" width="500" height="200" src=https://user-images.githubusercontent.com/89173945/149691486-db9bb4c0-d7db-4e39-aebd-8b58953de1e6.png><br><br><br><br><br><br><br><br><br>
_However, Lot 3, not surprisingly is a different scenario. Here the sample mean is 1496.14 and the p-Value is 0.04, which is lower than the common significance level of 0.05. All indicating to reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.<br><br>_
There has been some malfuction in Lot 3 prodution. There needs to be a check  in the processes, status system fails, and the suspension coils from this lot need to be inspected to remove those or repair those that are out of the requirements.




