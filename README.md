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
<img align="right" width="600" height="600" src=https://github.com/ChristianShada/MechaCar_Statistical_Analysis/blob/main/Resources/Box_Plot_IndividualLot.PNG>
