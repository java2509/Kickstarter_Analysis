###### kickstarter_analysis
An Analysis on Kickstarter Campaigns

![Screen Shot 2021-11-28 at 6 57 32 PM](https://user-images.githubusercontent.com/93900628/143793944-afe8bb7b-81ee-4395-b467-4b7075901f6c.png)

# Kickstarter Analysis

## Overview of Project

### Purpose
 
An up-and-coming playwright Louise started a crowd funding campaign to fund her play *Fever*, she managed to meet 86% of her goal of $2885 with an average donation of $248.5 backed by 10 donors in 28 days. Louise wants to know what the outcomes of other campaigns in relation to the launch dates and funding goals are. The purpose of our analysis is to use Kickstarter data of different campaigns and provide these insights in Excel with visual representation to Louise. The Kickstarter data we are looking at contains information of 4114 campaigns that launched from 2009-2017. The link below connects to the excel file with all the data,pivot tables and charts.

[Kickstarter_Challenge.xlsx.zip](https://github.com/java2509/kickstarter_analysis/files/7615386/Kickstarter_Challenge.xlsx.zip)

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The following steps were used to analyze different outcomes based on Launch Dates:

1.)	A year column was created in the Kickstarter Worksheet to extract the year from the “Date Created Conversion” column using the YEAR() formula.

<img width="771" alt="Screen Shot 2021-11-28 at 8 42 15 PM" src="https://user-images.githubusercontent.com/93900628/143800745-441472b3-9610-439e-9fde-7a40ec265ec4.png">

2.)	A pivot table was created using the Kickstarter Worksheet data, below is a screen shot of the field list:

<img width="298" alt="Screen Shot 2021-11-28 at 8 51 52 PM" src="https://user-images.githubusercontent.com/93900628/143801289-b7b26e77-d3be-4fc2-9d6c-b92788d2052a.png">

3.)	The Parent Category was filtered to show only data for the “theater” since Louise's play *Fever* is in the same Parent Category , column labels were filtered to show data for “successful”, “failed” and “canceled” campaigns. The campaign outcomes were sorted in descending order.

<img width="450" alt="Screen Shot 2021-11-28 at 9 10 36 PM" src="https://user-images.githubusercontent.com/93900628/143803076-e4b7cde8-e2c7-4285-bfb6-a0bec34325d8.png">

<img width="330" alt="Screen Shot 2021-11-28 at 9 28 24 PM" src="https://user-images.githubusercontent.com/93900628/143804362-21e6cb5e-367a-4b11-b733-b8793d933e6e.png">

4.)	A line chart was then created from the pivot table to visualize the relationship between theater outcomes and launch months. Below is the image of the line chart:

<img width="650" alt="Screen Shot 2021-11-28 at 9 34 20 PM" src="https://user-images.githubusercontent.com/93900628/143804805-dcc39fcf-1513-4bca-a6d9-33089c686484.png">

### Analysis of Outcomes Based on Goals

1.)	A new worksheet was created to analyze the percentage of successful, failed and canceled campaigns based on different goal dollar ranges. The COUNTIF () function was used to populate data in column’s B,C and D, based on the following columns in the Kickstarter Workbook, the “goal” amount column, the outcome column and the subcategory column using “plays” as a criteria since *Fever* falls in this subcategory.

<img width="1700" alt="Screen Shot 2021-11-28 at 10 45 55 PM" src="https://user-images.githubusercontent.com/93900628/143810466-818184a2-3c64-4966-ae33-f3d576cd99e8.png">

<img width="1700" alt="Screen Shot 2021-11-28 at 10 46 16 PM" src="https://user-images.githubusercontent.com/93900628/143810836-82c2f383-0179-44f9-b158-28b2467d9094.png">

2.) These were the results by each dollar amount range.

<img width="947" alt="Screen Shot 2021-11-28 at 11 12 43 PM" src="https://user-images.githubusercontent.com/93900628/143812596-2d2efa75-9136-46f6-af0f-25183373df8f.png">

3.)	A line chart was created to see the visual representation of the relationship between percentage of successful, failed, or canceled campaigns and the different ranges in goal amounts.See image below.

<img width="976" alt="Screen Shot 2021-11-28 at 10 59 30 PM" src="https://user-images.githubusercontent.com/93900628/143811687-adf66c2f-fba9-45a8-b66c-f6309f423098.png">

### Challenges and Difficulties Encountered



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1.) The two most successful champaigns were launched in in May and June.
 
  2.) The least successful time to launch a champaign would be in December where the number of failed champaigns is almost 
      equal to the number of successful champaigns. 


- What can you conclude about the Outcomes based on Goals?

  1.) The goal ranges with highest success is less than $1000 and $1000 to $4999, there are 529 successful campaigns out of a total of 720 in these ranges. The goal ranges between $30,000- $39,999 shows a 67% successful but the sample size is much lower with 6 out a total of 9.

- What are some limitations of this dataset?

1.) More parameters could be analyzed to determine what makes a successful campaign:
   - The genre's of plays that have had the most successful outcomes could be analyzed by subcategory.
   - The average donation and amount of backers supporting successful outcomes.
   - Using statisical measures to get rid of outliers that do not make sense to create a more realistic representation of outcomes.
 
- What are some other possible tables and/or graphs that we could create?

 1.) Successful campaigns based on Geograhic regions.





