# Kickstarting with Excel

## Overview of Project

### Purpose

Using the Kickstarter workbook [(download here)](https://github.com/Bulzeye89/Kickstarter_challenge/blob/main/Kickstarter_challenge.xlsx.zip) of over 4,000 
campaigns, we are interested in exploring relationships between both launch dates and funding goals to how different campaigns fared.  
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In order to look at outcomes based on launch date, one challenge was creating a Years column in the Kickstarter worksheet that we accomplished by using the Years function in excel by pulling it out of the date created conversion column .  With this new Year column, along with other columns created in our earlier analysis, a pivot table was created wtih Parent Category and Years for filters, Date Created for rows, Outcomes as columns, and counts of outcomes as values.  From this pivot table, the below graph was created. 

<img src="https://github.com/Bulzeye89/Kickstarter_challenge/blob/main/Resources/Theater_Outcomes_vs_Launch.png" width=50% height=50%>

### Analysis of Outcomes Based on Goals

To perform an analysis based on the campaigns' goals and the outcomes, we used countif formulas in a new worksheet to create a table.  I utilized data from the goal column, the outcome column and the subcategory column from the Kickstarter worksheet in order to create this table in order to count campaign successes and failures based on goal buckets that I set up in incremental buckets.  From this data, percentages were calculated that are displayed in the graph below.  

<img src="https://github.com/Bulzeye89/Kickstarter_challenge/blob/main/Resources/Outcomes_vs_Goals.png" width=50% height=50%>

### Challenges and Difficulties Encountered

While creating the table for the outcomes based on goals, some high dollar goals were observed on a small number of campaigns.  These campaigns were outliers in the data and a decision had to be made on whether to allow them to stay or be omitted.  Ultimately, in order to keep the integrity of the data intact, this data was left in on the analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - 25% of campaigns started in either May or Juen and these two months had the highest success rate as well.  February, April, and July had less campaigns started and had only slightly less success rates.  

- What can you conclude about the Outcomes based on Goals?
  - 68% of campaigns had a goal of less than $5,000 with a 73% success rate.  For best chances of success on future campaigns, I would adivse to take this into consideration.
  
- What are some limitations of this dataset?
  - The most recent data is from 2017 so more current trends may differ.  Also, this data only explores crowdfunding from one source.  It would be benificial to have data from various crowdfunding avenues in addition to the Kickstarter data. 
- What are some other possible tables and/or graphs that we could create?
  - I would be interested in taking a deeper look at the number of backers and the average donation per campaign.  Was there a higher or lower success rate for campaigns that had a lower number of backers with a higher donation amount or a higher number of backers with smaller donation amounts?  With current data, we wouldn't be able to calculate all measures of central tendency so more data would be needed to see what each individual backer donated.
  - We also could also take a look at the ideal time to keep a campaign open by looking at average length of both successful and failed campaigns.
