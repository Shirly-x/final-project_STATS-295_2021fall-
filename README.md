This is a project for the course STATS 295 where I analysed the data from 2020’s data analysis exam, which is a longitudinal data evaluating the effect of Zidovudine on CD4 cell counts. 
The primary scientific aim of this analysis is to tell whether the effect of treatment with Zidovudine can significantly reduce level of CD4 cell counts over time. In order to reach the conclusion, I proceed my analysis by: 
1. Visualizing the data structure of the given data by shadow matrix to show where are the missings and not missings. 
2. Imputing missing values by linear imputation and then visualizing the imputed values and non-missing values to see whether it’s reasonable or not. 
3. Grouping the data by age and visualize each group’s mean CD4 cell counts by contrasting Zidovudine treatment group and control group to tell whether the effect is significant. 
4. Using generalized estimating equations (GEE) with an appropriately chosen working correlation structure to quantify the effect of treatment with Zidovudine on the trajectory of CD4 counts over time.
