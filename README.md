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
When testing all three lots, at  the .05 confidence level, there isn't enough evidence to reject the null hypothesis, meaning there isn't a statistical difference between the means of the population and all manufacturing lots. However, when testing each lot individually, only lot1 and lot2 had statistically similar means to the population. There is enough evidence to reject the null hypothesis for lot3, the mean of lot3 is not equal to the mean of the population.<br>
<br>![image](https://user-images.githubusercontent.com/88811124/145734953-01c27c1d-bb6a-4d79-905d-2562399efa77.png)<br>
<br>![image](https://user-images.githubusercontent.com/88811124/145734978-82b5788c-ca7e-49c2-8015-a1cb30282ef8.png)<br>
<br>![image](https://user-images.githubusercontent.com/88811124/145734990-721fdac7-8315-4b64-aafc-0f378efbaa66.png)<br>
<br>![image](https://user-images.githubusercontent.com/88811124/145734997-07db92d0-91ff-493e-9cb7-6c939506c2f6.png)<br>
