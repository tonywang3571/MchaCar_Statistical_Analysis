# MchaCar_Statistical_Analysis

## Overview of Project  

**Purpose:**  
The purpose of this project is to create a webpage that will scrape current news article, facts, and images of Mars with a click of a button.  

## Resources:  
- Data Source: [](), []()  
- Software: R version 4.1.2, RStudio  

## Linear Regression to Predict MPG  
We preformed a [multiple linear regression model](https://github.com/tonywang3571/MechaCar_Statistical_Analysis/blob/master/Resources/linear_regression_summary.PNG) using RStudio. We calculated r-squared = 0.71 indicating a strong correlation between MPG and listed variables. The slope is not zero and dependent variables contribute to changes in mpg. We reject the null hypothesis (slope is zero and dependent variables do not effect changes in mpg) due to our low p-value = 5.35e-11. The PRr(>|t|) values of vehicle length (PRr(>|t|)=2.60e-12) and ground clearance (PRr(>|t|)=5.21e-8) are unlikely to provide random amounts of variance to our linear model. The intercept PRr(>|t|)=5.08e-8 also explains a significant amount of variablitliy in mpg when all other independent variables are zero. Due to the lack of significant variables in our data, we would take caution to not overfit our regression model. Overfitting can decrease our ability to predict and generalize future datasets and regression models, but would show good performance in our current dataset.  

## Summary Statistics on SUspension Coils  
Suspension coils were tested to determine if the manufacturing process is consistent across different lots. We calculated summary statistics for both the total and by lot numbers of the suspension coils.  
Summary statistics for the all of the suspension coils (includes all 3 lots):  
<img src="Resources/total_summary.PNG">  
Summary statistics for all 3 lots separated:  
<img src="Resources/lot_summary.PNG">  
The design specifications for the suspension coils must not exceed 100 PSI variance. We can see from our images that the total summary or combined summary (var=62.3 PSI) does meet the requirement of less than 100 PSI variance, but if we look at the lots separately, we can see that lot 3 (var=170 PSI) does not meet the requirement of less than 100 PSI variance.  

## Analysis and Results  

**Analysis:**  
For this project,  


**Results:**  
<img src="Resources/webpage1.PNG">  
<img src="Resources/webpage2.PNG">  

## Challenge Summary  

**Summary**  
The purpose of this project  


### Codes Used  
Please look at specific files for codes used  
Code for []()  
Code for []()  
Code for []()  
