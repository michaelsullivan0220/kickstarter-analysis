# An Analysis of Kickstarter Campaigns
### Performing an analysis on Kickstarter to uncover trends

## Overview of Analysis
### Purpose
Analyze kickstarter campaign information to 

## Analysis and Challenges
The dataset used for this analysis contained information on 4,115 kickstart campaigns across multiple fields of interest. For this report, we focused only on campaigns identifying as theatre. 
The data was filtered to only include theatre campaigns and was grouped by the month in which the campaign was initiated. This method provided the total quantity of campaigns initiated by month name (multiple years). The data was further organized to view the quantity of campaigns that had each of the following outcomes:
  - Successful
  - Failed
  - Cancelled

In addition to grouping this by the month, the data was also grouped by the *goal* amount that was specifed at the time the kickstarter was initiated. The quantity of each of the outcomes was captured across the following goal amount ranges:
  - Less than $1,000
  - $1,000-$4,999
  - $5,000-$9,999
  - $10,000-$9,999
  - $15,000-$9,999
  - $5,000-$9,999
  - $25,000-$9,999
  - $5,000-$9,999
  - $35,000-$9,999
  - $5,000-$9,999
  - $45,000-$9,999
  - $50,000 or more

Two analysis were completed as for this report and are described in more detail in the next sections. The data referenced was gathered from 1,363 kickstarter campaigns associated with theatre. This included plays, musicals and spaces. Data reference is from 2010-2017

### Analysis of Outcomes Based on Launch Date
#### Outcomes of Kickstarter Campaigns by Date Initiated (month)
The graph below shows the total number of successful, failed, and cancelled campaigns based on the month they were intiated. The month with the highest total campaigns intitiated (TCI) was the month of May with 163. This is followed by June (153) and July (138). Months with the lowest TCI are December (75), November(88), and March (92). 
May, June & July also saw the highest total of successful campaigns at 111, 100, & 87 respectively giving those months the highest probability to succeed. Campaigns started in May were successful in over two-thirds of of cases (66.9%). June (65.4%) and July (63.0%) show similar but slightly less success. the month with the lowest rate of success was December. Of all campaigns initiated in December, less than half (48.3%) went on to hit their goal. 

![outcome by date](https://github.com/michaelsullivan0220/kickstarter-analysis/blob/michaelsullivan0220-patch-1/Resources/Theater_Outcomes_vs_Launch.png)
*See Table 1.1 in Appendix for data included in the graph above.*

### Analysis of Outcomes Based on Goals
#### Outcomes of Kickstarter Campaigns by Goal Amount ($)
The graph below shows the total number of successful, failed, and cancelled campaigns based on the goal amount that was set when the campaign was intiated.
To draw meaninigful conclusions for this analysis, focus was put on campaigns with less than $10,000 goal amounts. 84.9% of all campaigns for plays had goal amounts of less than %10,000. Success rates for campaigns that had a goal amounts in the ranges of $35,000-$39,999 & $40,000-$44,999 were at 66.7% but cannot be confidently used as there were only 9 campaigns within these categories. 
Campaigns with a goal amount of less than $1,000 had the highest success rate at 75.81%. As expected, these rates decline as the goal amount increases. Campaigns with a goal amount of $15,000-$19,999 yielded a 50% success rate across 24 kickstarters.
The goal range with the most campaigns was $1,000-$4,999. 534 campaigns with a goal in this range saw a 72.6% success rate. 

![outcome by goal](https://github.com/michaelsullivan0220/kickstarter-analysis/blob/michaelsullivan0220-patch-1/Resources/Outcomes_vs_Goals.png)
*See Table 1.2 in Appendix for data included in the graph above.*

### Challenges and Difficulties Encountered
There were challenges that were encountered due to the lack of information associated with campaigns with a goal amount of greater than 10,000. Most of the campaigns (84.9%) were skewed towards less than $10,000. Goal amounts between $35,000-$45,000 had success rates of 66.7%, but had to be ignored due to only 9 kickstart campaigns being referenced. 

## Results
Starting a kickstarter campaign for a theatre project would have the best chance for success if intitiated in May, June or July. The data shows that a 65.2% chance of success for similar campaigns. In contrast, the holiday season should be avoided as a starting point. Campaigns initiated in Decemebr and through the new year into January had the worst rate of success at 54.3%.
Campaigns should be initiated with a goal amount of less than $5,000. Of all 720 campaigns that were listed under $5,000, 73.4% found success. 
Our recommedation is as follows: 

**A theatre campaign should be launched in May and have a goal amount of less than $5,000.**

The limitations of the data set restricts the confidence in recommending any campaigns over $10,000 goal value. Compared to the quantity of total campaigns, there are not enough campaigns with a goal amount over that value to draw any meaningful conclusions on success rates. 

Caution should be taken when following a recommendation for initiating a campaign in a specific month. Sorting the campaigns by month could potentially skew this information as the theatre industry revolves around its own cyclical season and is usually associated with holidays and large events. For example, we know that December has very low success rate but do not know if Christmas week provides some success. It is after all a very important time for the theatre industry. Is the success rate in June high because of a Memorial Day surge? **We recommend comparing outcomes vs. major US Holidays to determine if their is a correlation. This can be done by changing the date grouping and plotting major holidays over time**

## Appendix
*Table 1.1* 
Theatre Outcomes by Launch Date
| Month       | successful | failed | canceled | Grand Total |
| ----------- | ---------- | ------ | -------- | ----------- |
| Jan         | 56         | 33     | 7        | 96          |
| Feb         | 71         | 39     | 3        | 113         |
| Mar         | 56         | 33     | 3        | 92          |
| Apr         | 71         | 40     | 2        | 113         |
| May         | 111        | 52     | 3        | 166         |
| Jun         | 100        | 49     | 4        | 153         |
| Jul         | 87         | 50     | 1        | 138         |
| Aug         | 72         | 47     | 4        | 123         |
| Sep         | 59         | 34     | 4        | 97          |
| Oct         | 65         | 50     |          | 115         |
| Nov         | 54         | 31     | 3        | 88          |
| Dec         | 37         | 35     | 3        | 75          |
| Grand Total | 839        | 493    | 37       | 1369        |

*Table 1.2* 
Outcomes by Goal Amount
| Goal  (in dollars) | Number Successful | Number Failed | Number Canceled | Total Projects |
| ------------------ | ----------------- | ------------- | --------------- | -------------- |
| Less than 1000     | 141               | 45            | 0               | 186            |
| 1000 to 4999       | 388               | 146           | 0               | 534            |
| 5000 to 9999       | 93                | 76            | 0               | 169            |
| 10000 to 14999     | 39                | 33            | 0               | 72             |
| 15000 to 19999     | 12                | 12            | 0               | 24             |
| 20000 to 24999     | 9                 | 11            | 0               | 20             |
| 25000 to 29999     | 1                 | 4             | 0               | 5              |
| 30000 to 34999     | 3                 | 8             | 0               | 11             |
| 35000 to 39999     | 4                 | 2             | 0               | 6              |
| 40000 to 44999     | 2                 | 1             | 0               | 3              |
| 45000 to 49999     | 0                 | 1             | 0               | 1              |
| Greater than 50000 | 2                 | 14            | 0               | 16             |

