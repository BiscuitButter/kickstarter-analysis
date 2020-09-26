# Kickstarting with Excel

## Overview of Project
An analysis of Kickstarter campaigns from 2009 to 2017. 

### Purpose
The purpose of this analysis is to help a young playwright, Louise, create a successful Kickstarter campaign for her upcoming play *Fever*. Her estimated budget is $10,000. 

## Analysis and Challenges
This analysis highlights the best time to start a fundraising campaign for theatrics as well as the optimal Goal range for a play. To get a clear picture, new information had to be extracted from the preexisting data. This was accomplished by converting nonstandard date formats into something recognizable and by building new tables with data that was relevant to the client’s needs.

### Analysis of Outcomes Based on Launch Date
![Theater Outcomes vs Launch Date Chart](https://github.com/BiscuitButter/kickstarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals
![Outcomes vs Goals Chart](https://github.com/BiscuitButter/kickstarter-analysis/blob/master/Resources/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered
As an experienced Excel user, I felt comfortable with the work in this Module. If something was going to give me a headache, I imagine it would have been getting the COUNTIFS formula to work correctly for Outcomes Based on Goals.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The optimal time to have a fundraiser is around the month of May. 
  2. The chances for success decrease considerable during the colder months.

- What can you conclude about the Outcomes based on Goals?

  Generally speaking, lower goals have greater success. There is an anomaly between $35k - $45k where the success rate is about 66%. However, the chart doesn’t reveal how many campaigns make up that data point. If there are only three campaigns contributing to that data point, then the results cannot be considered reliable. I think if this was presented as Number of Successes/Failures as opposed to Percentage of Successes/Failures it would be a little less deceptive.

- What are some limitations of this dataset?

  Results are likely to vary based on geographical location. While the Kickstarter data does provide the Country of the campaign, it doesn't show the local region. I may drive 50-100 miles to see a play that I am really excited about. Any further and I probably won't consider it.

- What are some other possible tables and/or graphs that we could create?
  1. Outcomes of Launch Dates by Country
  2. Outcomes of Goals by Country
  3. Campaign Duration
