# Kickstarting with Excel
## Overview of Project  
An analysis of kickstarter data to uncover trends for theater (play) campaigns based on funding goal and also launch date.
## Purpose
The purpose of this project was analyze kickstarter campaigns for "Louise" to help Louise make an informed decision about her own campaign.  We narrowed the data to campaigns similar to our target campaign: theater projects with an emphasis on plays.  The analysis sought to answer the following two main questions:
1. Does the month that a campaign is launched affect how successful the kickstarter is?
2. Does the initial funding goal affect how successful the kickstarter is?
## Analysis and Challenges
The initial dataset included data on over four thousand crowdfunding campaigns from 2009-2017.  An analysis was done on the campaigns to categorize the data by outcome, country, funding goal, category and many others.  It was determined that several campaigns matched our target campaign of theater projects: plays. I used data filtering in Excel to filter out campaigns that didn't match our target.  
### Analysis of Outcomes Based on Launch Date
I created a pivot table based on the entire sheet of data filtering by Parent Category and Month:
![Pivot Table](Resources/Launch_Date_Pivot_Table.PNG)
After creating the pivot table, I created a line graph based on the information to display the number canceled, failed, live or successful campaigns based on the month the project launch.
![Line graph]Resources/Theater_Outcomes_vs_Launch.png
### Analysis of Outcomes Based on Goals
To analyze outcomes based on goals, I used the countifs command to create a count of projects based on funding goal and successful vs. failed outcomes.  This is an example of the code I used:
`=COUNTIFS(Kickstarter!$D:$D,"<4999",Kickstarter!$D:$D,">=1000",Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays")`
### Challenges and Difficulties Encountered

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?


