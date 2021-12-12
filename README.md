## Linear Regression to Predict MPG
1. The vehicle_length and ground_clearance provided a non-random amount of variance to the mpg values in the dataset at the .05 confidence level.
2. The slope of the linear model is not considered to be zero due to the models p-value, 5.35e-11, being less than .05. This is enough evidence to reject the null hypothesis.
3. The model does effectively predict the mpg of prototype MechaCars. The r-squared value of .7149 means that ~71% of predictions will fall within the moodel. <br>
<br>![image](https://user-images.githubusercontent.com/88811124/145729365-4f816247-893d-4918-95cf-26690cd2a3df.png)

## Summary Statistics on Suspension Coils
In total, the 3 lots are well within the 100 PSI variance requirement. However, when grouping by lot, only lots 1 and 2 are performing as they should. Lot 3 experiences significantly higher variance and is not within the 100 PSI variance requirement. <br>
<br>![image](https://user-images.githubusercontent.com/88811124/145731268-b609e4eb-7173-4707-9687-5a7859c16515.png)<br>
<br>![image](https://user-images.githubusercontent.com/88811124/145731278-fb14df63-5d18-481e-adb0-673f00e64ab6.png)

## T-Tests on Suspension Coils
