# kickstart-analysis
## Overview of the Project
Louise is a client. She is a playwright who wants to launch a fundraising campaign for her next play titled FEVER. She has a budget of little over $10,000.00.  
### Purpose
Purpose of this project it to analyze data gathered and to determine if we can help Louise achieve a successful outcome based on her budget. 
## Analysis and Challenges
When analyizing the data some of the challenges I encountered was the Data set included data we really didn't need to get what we were wanting to look at. Also some conversions needed to be made to make it readable to the average person. I wanted to narrow my analysis down to Theater/Plays and Goal amount for successful and failed outcomes on a project. I also wanted to narrow it down by analyzing the OUtcome success based on Launch dates.  I had to use the YEAR function to pull the year from Date created.  
I performed my analysis by organizing some data into seperate tables, creating charts and tables to help me narrow down specific data. 
I would also create visual charts to display the data and it would help me gather more detail by using specific formulas to make some calculations. I did encounter some issues when creating charts due to my main data sheet being in filter or sort mode and so I would need to clear that when appropriate so it would capture all my data. 

### Analysis of Theater Outcomes Based on Launch Date
I analyized this data by creating a pivot table from my main dataset (Kickstart). With the pivot table I focused on Theater adn Years. We did not have a years column of data set and used the function to extract the year from Date Created column.  This narrowed it down from a long date to just the year the campaign was created. I then set up my pivot taable to gather the data I wanted such as Parent Category, Years and Outcomes. I ran into the Years had some options so I specifically chose Month in the pivot TABLE. Using the pivot table I created a line chart that showed me visually the Theatre Outcome status Based on Launch Date(Date Created).  
-Two conclusions about the Outcomes Based on Launch Date 
    1.The Theater Category had doubled successful outcomes in comparison to failed outcomes.
        May is a good time to campaign. 
    2.There was a decrese in Failed outcomes and slight increase in Successful outcomes in month of October just to make December Successful and Failed were both the same at about 50%. 

### Analysis of Outcomes Based on Goals
Looking at the percentage of outcomes (Successful,Failed, and Canceled) plays based on the funding goal amount. We created a new table with the Goal data range and the number of Outcomes and Percentage of Outcomes. This we did on a seperate sheet titled "Outcomes Vs Goals"
the chart was used for making calculations. We used the Countifs function to helps us soperate the data within the Goal Column of main Dataset(Kickstart). We then created a line chart titled OUtcomes_Vs_Goals. 
-Conclusion based on the Outcomes based on Goal was that the most successful outcome on a play project campaign was when the goal amount was in the range of $35,000 to $39,999. 


### Challenges and Difficulties Encountered

## Result

-Two conclusions about the  Based on Launch Date are
   1.The Theater Category had doubled successful outcomes in comparison to failed outcomes.
        May is a good time to campaign. 
    2.There was a decrese in Failed outcomes and slight increase in Successful outcomes in month of October just to make December Successful and Failed were both the same at about 50%. 

-Conclusion based on the Outcomes based on Goal was that the most successful outcome on a play project campaign was when the goal amount was in the range of $35,000 to $39,999. 


-Some of the limitations of this dataset are...too much unneeded data, some conversions need to be made on some of the data to make it readable. Needed to add some data to original data. 

-Some other possible tables and bar graphs that you could create would be a bar graph on percentage of outcomes based on Goal Range. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/94208![ParentCategoryOutcomes](https://user-images.githubusercontent.com/94208810/141657673-999208f3-db7e-44aa-9dcd-78323808897d.png)
810/141657667-860969a4-dc0a-4e98-818d-b868eacdcdb3.png)![Theater_Outcomes_vs_Launchdate](https://user-images.githubusercontent.com/94208810/141657676-2da7d5e3-56c5-4cdf-8cb6-131dc1f5a71c.png)

