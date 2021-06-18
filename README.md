# Kickstarter-Analysis
## Overview of Project
Performing Analysis on Kickstarter data to uncover trends.
### Purpose
The purpose of this analysis to inform Louise on how different campaigns fared in relation to their launch dates and their funding goals.
## Analysis and Challenges
This analysis used two methods to evaluate how different campaigns in relation to one another: launch date and goals. While the criteria illustrated some trends, they also suggested some challenges.   
### Analysis of Outcomes Based on Launch Date
To begin this analysis it was necessary to add a column of years to original Kickstarter data. This was done using the YEARS() function so that is could be an additional variable when evaluating the "Date Created" Column. Next, a pivot table was created to further analysis success in relation to launch date.

<img width="327" alt="Screen Shot 2021-06-18 at 1 58 08 PM" src="https://user-images.githubusercontent.com/84995704/122605785-8b162980-d03d-11eb-8dbc-321b0d5e8431.png">

To futher understand the relationship between launch date month and outcomes a line chart was created as well. 
Theater_Outcomes_vs_Launch.png![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/84995704/122606185-20b1b900-d03e-11eb-8bcc-cf3e4a5deda9.png)
This line chart, when coupled with the pivot table, helps illustrate the difference between those plays that demonstrate success versus failure. 
### Analysis of Outcomes Based on Goals
In this analysis, a new sheet was created to evaluate outcomes based on goals using data such as number Successsful/Failed/Canceled, goal, and percentage Successful/Failed/Canceled. The COUNTIFS() functions was used to populate Successful/Failed/Canceled, as well as filters to further refine the data. Then, the SUM() function was used to populate the total projects for each respective outcome category. 
Outcome_vs_Goals<img width="713" alt="Outcome_vs_Goals" src="https://user-images.githubusercontent.com/84995704/122608627-29a48980-d042-11eb-88b1-02b511a399c6.png">
### Challenges and Difficulties Encountered
If you had no challenges, describe any possible challenges or difficulties that could be encountered.
## Results
