## Analysis of the pharmaceuticals data with Pandas and Matplotlib
### Technologies Used
- Pandas
- Matplotlib

### Analysis
- **Data Cleaning** - Ensured there are no duplicate data in the dataset.
- Generated summary statistics table of mean, median, variance, standard deviation and SEM of the tumor volume for each drug regimen.
- Generated various plots to observe any trends in data.
- Calculated the final tumor volume of each mouse across four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
- Calculated the quartiles and IQR and quantitatively determined if there are any potential outliers across all four treatment regimens.
- Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 

### Observations and Insights
- The tumor volume for the mice seem to decrease only for drug regimens Capomulin and Ramicane. For other drug regimens, the tumor volume increases with the timepoints. The number of mice treated with Capomulin and Ramicane drugs were more than any others. The Standard Deviation calculated for the various drugs shows that tumor volume data for Capomulin and Ramicane drugs are smaller which implies the data is distributed over a smaller range than other drug types.
![Boxplot](https://github.com/itspria/Pharmaceuticals-Drug-Analysis/blob/main/images/boxplot.PNG)
Sample plot for Capomulin regimen
![Sample](https://github.com/itspria/Pharmaceuticals-Drug-Analysis/blob/main/images/sample.PNG)

- The number of female and male mice used for the study was almost the same. There is no significant difference in tumor volume changes across the gender of the mice.
 
![Mice Gender Plot](https://github.com/itspria/Pharmaceuticals-Drug-Analysis/blob/main/images/gender.PNG)
![Mice Gender Count Plot](https://github.com/itspria/Pharmaceuticals-Drug-Analysis/blob/main/images/count.PNG)

- The correlation coefficient of weight and tumor volumes of the mice in Capomulin group is 0.84 which is closer to 1, which implies as the weight of the weight of the mouse increases the average tumor volume also increases in most cases.

![Correlation](https://github.com/itspria/Pharmaceuticals-Drug-Analysis/blob/main/images/correlation.PNG)

- The age of the mice does not have any relation with tumor volume changes
