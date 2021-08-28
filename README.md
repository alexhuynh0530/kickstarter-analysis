# An Analysis of Kickstarter Campaigns

## Overview of Project

### Purpose

This analysis is to help an up-and-coming playwright, Louise, who wants to start a crowdfunding campaign to help fund her play - Fever. She's estimating a budget of over $10,000. By using Excel, we analyze crowdfunding data to determine whether there are specific factors to make a project's campaign successful. We take a look at the crowdfunding outcomes based on launch dates as well as the outcomes based on the fundraising goals set for the campaigns. These insights are used to help Louise gain a greater understanding of past crowdfunding campaigns so that she can mirror other succcessful campaigns in her category. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch.png](https://github.com/alexhuynh0530/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

The line chart above illustrates the outcomes of campaigns in the theater category versus the date they launched using months of the year. Based on the chart, we can see that May was the most successful month to launch. You can also see that Decemeber had the lowest success rate. Although May has the greatest number of failures, please note that May also had the greatest total number of campaign outcomes with 166.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals.png](https://github.com/alexhuynh0530/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

The line chart above illustrates the outcomes of campaigns versus the fundraising goals they set. Based on the chart, we can see that campaigns with goals less than $5,000 had higher success rates. Specifically, campaigns with goals less than $1,000 had 76% success, and campaigns with goals between $1,000 and $4,999 had 73% success. On the other hand, you can see that campaigns with higher goals above $45,000 had a higher rate of failure. Campaigns with goals between $45,000 and $49,999 had 100% failure, and campaigns with goals greater than $50,000 had 88% failure.

You'll also notice that goals set between $35,000 and $44,999 had a relatively high success rate at 67%. Although the sample size within these groups are small, this could indicate that there are other important factors other than fundraising goals that play a part in successful campaigns.

### Challenges and Difficulties Encountered

It is challenging to make sense of data anomalies. For example, in the line chart and analysis above for Outcomes Based on Goals, it is clear that goals less than $5,000 had higher success rates and goals above $45,000 had lower success rates. However, goals set between $35,000 - $44,999 had relatively high success rates. It's difficult to conclude why this group still held a high success rate without more information given. Some of the successful campaigns had a relatively small amount of backers while others had many. They also launched during different parts of the year. Perhaps the playwrights of these plays were well-known so networking/fundraising came easier. Or perhaps the marketing/promotion was higher quality or using a specific profitable method. We know that fundraising goals play a part into a campaign's success, but there are other factors that contribute as well. 

## Results

### Conclusions made about the Analysis of Outcomes Based on Launch Date

- Campaigns launched in May had the highest number of successful campaigns
- Campaigns launched in December had the lowest number of successful campaigns

### Conclusions made about the Analysis of Outcomes Based on Goals

- Fundraising goals of less than $5,000 had the highest success rates
- We could also conclude that other factors other than fundraising goals play a part in a successful campaign as we saw goals set between $35,000 and $44,999 also having high success rates

### Summary

There are some limitations to this dataset that include:

- Data limited to only 2010-2017, fresher data could help with more recent years
- Lack of data about the form of marketing and promotion used in executing the campaign fundraising (i.e. email marketing, social media, etc.)

Another graph we could create could be another line graph of Theater Outcomes by Launch Date using percentages. As noted in the Analysis of Outcomes by Launch Date, the most successful campaigns launched in May. However, May also had the most failed campaigns by quantity. If we used percentages, we would see that May had the highest percentage of successful campaigns (67%) followed by June (65%), and December had the highest percentage failed (47%) followed by October (43%). To enhance this chart even further we could filter on goals with about $10,000 since Louise is budgeting over $10,000 for her campaign.
