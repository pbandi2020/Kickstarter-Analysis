# Kickstarter Data Analysis
## Overview of Project
This document outlines the project analysis and how data can be leveraged to make business decisions and how data can be utilized to Visualize the Current, Past and Future state of the business operations. In this experience we focused on the following 2 outcomes.

### Purpose

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
* Louis would like to know what our current campaign outcome is based on the actual campaign launch date. She wants to visualize the campaign outcome by Launch Date / for a period of time. Also, she is looking for the ability to filter the data by category and year. Below is the snapshot of the data table and the line graph showing the visual view of the same data. 
* Let’s compare a single data point to help understand what is inferred from the graph and data table below. Even though the chart below shows May as the most successful month for the category Theater, the outcome is measured across multiple years. When you add the Year dimension in the filter criteria the graph may look different and May not be the most successful month in the result set. So, the result of what you infer and interpret would depend on what you are trying to learn from the below model. The grain of the data is what helps slice and dice the result set to view various models of the same data.

![OutcomesBasedOnLaunchDateANDCategory](/Resources/Theater_Outcome_Vs_Launch.png)

![GraphVsDataviewAnalysis](/Resources/LaunchDate_Analysis.png)

### Analysis of Outcomes Based on Goals
* In this model Louis would like to know what our original goal for the campaign was and what percentage of the outcome met our goal. Below is the snapshot of the data table and the line graph showing the visual view of the same data. 

![OutcomesBasedOnLaunchDateANDCategory](/Resources/Outcomes_Vs_Goals.png)

### Challenges and Difficulties Encountered
* Deliverable 1 – No major challenge as this was an exercise that was done in the class work assignment other than the fact, I had to play around a little with the chart attributes.
* Deliverable 2 – Manual entry of range and the formula setup was the challenge. After completing one set of formula all others were more copy and paste. No major challenges. The video on CountIF function was helpful was we did not look at this formula in class. Since I has programming experience I was able to get the multi condition where class and knew how to calculate the percentage was able to complete, For anyone with no SQL experience might have had trouble with the CountIF function in this deliverable.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Total campaign responses are 1369 and 24 are still in progress/Live which can fall into one of the outcome categories of Success, Failed or Cancelled for the Theater category
  - The overall campaign outcome across all categories are 4114 with only 50 waiting on outcome. Over 25% of the campaign are for the Theater category and 50% outstanding outcome is in the theater category. 


- What can you conclude about the Outcomes based on Goals?
** Every Campaign conducted had a positive or negative outcome with highest success rate in the goal range of $1000 to $4999. For future campaigns, the business goals can realign to this range to drive more dollars and meet the campaign goal.

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
