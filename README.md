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
Again, a line chart, when coupled with the table, helps illustrate the negative relationship between those play perecentage of successful and failed plays, and the goal of plays overall. 

![image](https://user-images.githubusercontent.com/84995704/122608932-bd765580-d042-11eb-82ed-b61d2ef6070c.png)
### Challanges and Difficulties Involved

There were no incredible challenges involved in the analysis, though, there was some abrasion, most of which occured in creating the line charts. The x and Y axes needed to be reversed in order to get an accurate picture of the outcomes based on goals. Also, categories considered, "noise," needed to be filtred in order to get a clearer picture of the data needed to make an accurate analysis.
## Results
  In the Theater Outcomes by Launch Date data, there are two conclusions that can be assessed. First, the months of April and August show the greatest disparity between failed and successful outcomes, leading to the assessment that those two months are the best in terms of a successful outcome based on launch date. Second, in terms of course of an entire year, both successful and failed plays follow a similar path, that is, plays generally start weaker in winter months and stronger in the summer months. 
    In Outcomes Based on Goals, it is easy to make the conclusion that there is a both negative and positive relationships between percentage successful and percentage failed when compared to the size of the goal. As the goal amount increases, the percentage successul decreases while the percentage failed increases. So, percentage failed has a postive relationship when the goal amount increases, and percentage successful has a negative relationship when the goal amount increases. The overall conclusion is that plays with a lower goal have a greater chance at success.
    There are many limitations, still. For example, there is not enough data to explain why exactly low goals lead to greater success. Do donors write off lofty goals? Are those who plan tighter budgets more pragmatic, or do they provide a higher overhead in profit? Also, when looking at the launch date data, questions concering the summer months are spurred about audience spending habits, holiday months, free time, etc., in addition to weather, types of venue, and so on. Perhaps a table showing the the finances would aid a bit, such as an initial budget compared to monthly debit and credit of accounts. 
