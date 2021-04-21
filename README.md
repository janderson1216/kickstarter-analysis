# Kickstarting with Excel

## Overview of Project
 Analyzing Kickstarter success for theater related campaigns.

### Purpose
Assess and visualize Kickstarter data to show correlation between campaign outcomes and its launch date and fundraising goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I looked at campaign outcomes based on launch date by creating a table that lists the number of campaigns in each outcome category, based on the month of launch date. I then used that information to create a line graph to better show the months with the most successful campaigns.

![theater_outcomes_vs_launch](Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

I created a chart to show the percentage of successful, failed and canceled campaigns within several fundraising goal ranges. This chart helps to gain an  understanding of goal amounts that are most attainable.

 The percentage of successful, failed and canceled campaigns based on fundraising goals is visualized below. 

![outcomes_vs_goals](Resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
A challenge I experienced was using the COUNTIFS() function in excel. Initially, I kept getting zero as the result. Through filtering in the Kickstarter worksheet I was able to tell that my formula was wrong. After a few attempts, I realized that I was giving the criteria of “play” instead of “plays.” The criteria has to be exact to pull correct data. Also, something that I found to be super helpful was actually saying the criteria aloud while typing, if helped me to ensure I inputted the correct criteria and range. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   - (1) The greatest number of successful campaigns are launced in May.
   - (2) Campaigns launched in October have a higher chance of failing, as almost half of October campaigns failed. 

- What can you conclude about the Outcomes based on Goals?
   - Campaigns with fundraising goals between 35k-45k are the most sucessful.

- What are some limitations of this dataset?
   - (1) The data does not show if there are more successful campaigns in May because of the increase in the number of campiagins or if campaigns do better during that time of month. 

- What are some other possible tables and/or graphs that we could create?
   - (1) Graph and table that shows the percentage of successful, failed and canceled plays based on Kickstarter launch date. 
