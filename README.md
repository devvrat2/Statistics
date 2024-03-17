Instruction
=
Please use the Data.xlsx file to investigate the effect of independent variables (price per square foot, number of bathrooms, and floor size) on the price of a high-floor, spacious 2-bedroom house with a spectacular view, available at an affordable price. The null hypothesis (H0) states that there is no significant effect of the independent variables on the price. The alternative hypothesis (H1) suggests that there is a significant effect of the independent variables on the price. The objective is to test this hypothesis using the provided data in the "Data" Excel file.
 
Selection of Confidence Level: A 95% confidence level is chosen to determine the range within which the true parameter value is likely to fall. A 95% confidence interval covers 95% of the normal curve, meaning that there is a 5% probability of observing a value outside of this range.

 Statistical Test or Model: To test the hypothesis, a multiple regression analysis is conducted. This analysis helps determine the relationship between the dependent variable (price) and the independent variables (price per square foot, number of bathrooms, and floor size).

Click here to download the data set
https://kh3-ls-storage.s3.us-east-1.amazonaws.com/Dataset_1.xlsx

Solution
=

SUMMARY OUTPUT								
								
Regression Statistics								
Multiple R	0.992557583							
R Square	0.985170555							
Adjusted R Square	0.985044881							
Standard Error	2297.767962							
Observations	358							
								
ANOVA								
	df	SS	MS	F	Significance F			
Regression	3	1.24166E+11	41388611948	7839.141832	0			
Residual	354	1869027113	5279737.608					
Total	357	1.26035E+11						
								
	Coefficients	Standard Error	t Stat	P-value	Lower 95%	Upper 95%	Lower 95.0%	Upper 95.0%
Intercept	-97558.76481	1269.713415	-76.8352635	7.0533E-223	-100055.8948	-95061.6348	-100055.8948	-95061.6348
FLOOR_SIZE	69.69929534	0.647815907	107.591207	1.7487E-272	68.42524364	70.97334704	68.42524364	70.97334704
NO_OF_BATHROOMS	496.9900137	245.6948562	2.022793726	0.043845756	13.78491374	980.1951136	13.78491374	980.1951136
PRICE_SQFT	1368.674756	11.09522401	123.3571089	5.8314E-293	1346.853913	1390.495599	1346.853913	1390.495599
![image](https://github.com/devvrat2/Statistics/assets/157883632/6b60323d-8270-4d10-9a3f-4d22f529f274)

"5% probability of observing a value outside of the confidence interval or 95%confidence

FLOOR_SIZE:
The very low p-value (1.7487E-272) for FLOOR_SIZE indicates that this variable is highly statistically significant. There is strong evidence to suggest that the floor size has a significant effect on the house price.

NO_OF_BATHROOMS:
The p-value (0.043845756) for No. of Bathrum is less than 0.05, suggesting it is statistically significant at a 95% confidence level. There is also evdience that it is significant

PRICE_SQFT:
The extremely low p-value (5.8314E-293) for PRICE per sqft indicates that this variable is highly statistically significant. There is strong evidence to suggest that the price per square foot has a significant effect on the house price."								

