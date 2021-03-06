# Kickstarter Data Analysis
## Overview of Project
This document outlines the project analysis and how data can be leveraged to make business decisions and how data can be utilized to Visualize the Current, Past and Future state of the business operations. In this experience we focus on following dimensions and facts.
  * Measure the Outcome/Results based on Campaign Launch Date
  * Measure the campaign goal based on the campaign outcome

### Purpose

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
* Louis would like to know what our current campaign outcome is based on the actual campaign launch date. She wants to visualize the campaign outcome by Launch Date / for a period of time. Also, she is looking for the ability to filter the data by category and year. Below is the snapshot of the data table and the line graph showing the visual view of the same data. 
* Let’s compare a single data point to help understand what is inferred from the graph and data table below. Even though the chart below shows May as the most successful month for the category Theater, the outcome is measured across multiple years. When you add the Year dimension in the filter criteria the graph may look different for the month of May and may not be the most successful month in the result set. So, the result of what you infer and interpret would depend on what you are trying to learn from the below model. The grain of the data is what helps slice and dice the result set to view various models of the same data.

![OutcomesBasedOnLaunchDateANDCategory](/Resources/Theater_Outcome_Vs_Launch.png)

![GraphVsDataviewAnalysis](/Resources/LaunchDate_Analysis.png)

### Analysis of Outcomes Based on Goals
* In this model Louis would like to know what our original goal for the campaign was and what percentage of the outcome met our goal. Below is the snapshot of the data table and the line graph showing the visual view of the same data. 

![OutcomesBasedOnLaunchDateANDCategory](/Resources/Outcomes_Vs_Goals.png)

### Challenges and Difficulties Encountered
* The orginal data table did not have the data columns needed to derive the resultset and hence had to convert the Launch Date, Category & Subcategory columns. 
* CountIF function, had to research on how to write multiple condition
* Readme file formating commands had to google to find out formating rules
* Picture upload to GitHub was challenging.
* Was able to overcome the challanges using google and Slack comments.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Total campaign responses are 1369 and 24 are still in progress/live which can fall into one of the outcome categories of Success, Failed or Cancelled for the Theater category
  - The overall campaign outcome across all categories are 4114 with only 50 waiting on outcome. Over 25% of the campaign are for the Theater category and 50% outstanding outcome is in the theater category. 


- What can you conclude about the Outcomes based on Goals?
  - Every Campaign conducted had a positive or negative outcome with highest success rate in the goal range of $1000 to $4999. For future campaigns, the business goals can realign to this range to drive more dollars and meet the campaign goal.

- What are some limitations of this dataset?
  - Measuring the campaign outcome without duration as a dimension is a disadvange. As a results, outcome has to be compared at a given point in time to understand the retention and success rate. In our analysis we are measuring over a long period of time which really does not provide accurate measure to validate success rate.

- What are some other possible tables and/or graphs that we could create?
  - We can view the outcome by Category & Subcategory
  - We can view the outcomes by country 
  - We can view the outcomes by Backers Count
  - Goal exceeded the actual pledged
