# Kickstarting with Excel

## Overview of Project
Analysis and visualization of Theater (N = 1369) and plays (n = 1047) fundrising campaign data.
### Purpose
The client's play "Fever" came close to reaching its fundraising goal in a short amount of time. Now, she wants to know how similar campaigns fared in relation to their launch dates and their funding goals. The purpose of this analysis is to create a visualization for different theater and plays campaigns based on launch dates and funding goals. Conclusions will be made based on the visualization of this dataset and suggestions offered for further analysis of data.
## Analysis and Challenges
### Analysis of Theater Outcomes Based on Launch Date
A pivot table was created with filters (parent category, and months) and filtered to show data only for parent category "theater" campaigns. Outcomes placed in the columns included successful (n = 839), failed (n = 493) and canceled projects (n = 37). Rows were created to extract the year from the "Date Created Conversion" and sorted in ascending order based on month. Finally, a line chart was created to visualize the relationship between outcomes (successful, failed, and canceled theater projects) and launch month (January through December).

![Theater_Outcomes_vs_Launch](resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Plays Outcomes Based on Goals
Columns were created to show the number of successful (n = 694), failed (n = 353) and canceled (n = 0) plays campaigns relative to their fundraising goal in dollar-amount ranges. The goal column was created to show the following dollar-amount ranges (less than 1000, 1000 to 4999, 5000 to 9999, 10000 to 14999, 15000 to 19999, 20000 to 24999, 25000 to 29999, 30000 to 34999, 35000 to 39999, 40000 to 44999, 45000 to 49999, and greater than 50000). Next percentages were calculated based on outcome/total projects for goal. Finally, a line chart was created to visualize the relationship between outcomes based on fundraising goals.

![Outcomes_vs_Goals](resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
Difficulties for Deliverable 1 included not getting the pivot table to look 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Conclusion #1: The most successful month for Theater campaigns was May (111). Based on the dataset it can be concluded that May is the best time to launch a successful Theater campaign.
  - Conclusion #2: The least successful month for Theater campaigns was December (37). Based on the dataset it can be concluded that December is the worst time to launch a successful Theater campaign. 
- What can you conclude about the Outcomes based on Goals?
  - Conclusion #1: When the goal was more than $45,000, there were only 2 successful play campaigns, and 15 failed play campaigns, resulting in the largest discrepancy between fundraising goal dollar amounts between successful and failed play campaigns.
  - Conclusion #2: The highest percentage of successful play campaigns was achieved with a goal of less than $1000 (76%), followed by $1000-$4999 (73%), followed by a tie between $35000-$39999 and $40000-$44999 (67%)

- What are some limitations of this dataset?
  - Donor information is not available in this dataset. By including what type of donor contributed (individual, corporate, foundation, non-profit, or government) further targeted analysis can be made to see if type of donor had a significant relationship with fundraising goal or launch date.
  - US (n = 900), GB (n = 353), Canada (n = 44)

- What are some other possible tables and/or graphs that we could create?
-   Play outcomes based on Launch date
-   
