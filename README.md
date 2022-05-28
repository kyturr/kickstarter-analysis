# Kickstarting with Excel

## Overview of Project
This project takes an array of data collected about Kickstarter campaigns and utilizes pivot tables, graphs and equations in order to create an easily accessible and readable set of worksheets so that trends and insights can easily be seen. 

### Purpose
The purpose of this project was to gather research for the upcoming campaign for the play "Fever". Utilizing the full range of data as well as filtered data, many trends are able to be seen which may aid in the campaigns decisions. This project also demonstrates how excel can be used effectively for data analysis.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103979048/170812437-04bf1096-5e48-43eb-a8cb-498f03bb4135.png)

From the included graph it is clear to see that the months of May and June are the most popular times to launch a theater campaign. In fact, the greatest number of successful theater campaigns were launched in May. This also seems to be where the largest gap between successful and failed campaigns lies. One additional insight that is clear to see is that campaigns launched in December were the least successful as it is the only point in the graph where there were almost as many failed campaigns as successful ones. Finally, it is clear that in  every month, theater campaigns had more successes than failures, so there is a greater likelihood of the campaign succeeding.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103979048/170812440-fb642429-03c7-4e29-98b4-274266a5be68.png)

From this graph it is clear to see that the success rate of the campaigns decreases as the goal increases to the point where in the range of $15-20k there are more failed campaigns than successful ones. There does seem to be a small spike of success in the $30-40k range. Given that the play “Fever” is looking at a budget of around $10k, it is slightly favorable to launch at this goal. However, if there is a way to cut some of the budget it is over 3% more successful to launch in the $5-10k range, leading to an increased likelihood of the project succeeding in obtaining funding.
### Challenges and Difficulties Encountered

In this challenge, there was slight difficulty working with the countifs function. Setting up the ranges did not work as expected. To overcome this, I examined the examples closer and also looked up some syntax examples online. From this I was able to find the error in my function and correct it. I can foresee that in the future if in a challenge we were asked to use new functions that we were less familiar with we might encounter these initial difficulties with how to implement the functions but these difficulties can similarly be overcome by closely looking at the examples and looking up additional examples.

## Results

There are two pertinent conclusions that can be made from examining the Outcomes based on Launch Date graph. First, if possible Louise should aim for an early summer launch date in May or June because this is the most successful launch period for theater campaigns. Second, Louise should avoid a December launch since there are almost as many failed campaigns as successful campaigns launched that month.

For Louise and “Fever” there is one conclusion that can be made from the Outcomes based on Goals graph. Since the initial projected budget is around $10k Louise should aim to cut the budget down not expand it. The success rate for $5-10k is 3% greater than campaigns launching with a goal of $10-15k.

One limitation of the data set is that it can only track quantitative data, where backing a kickstarter campaign involves qualitative decisions as well as quantitative decisions. A campaign can run in all the positive categories, budgets, and timings but if it is just a bad idea it will still fail. Another limitation to this data set is its relative age as the data is 5 years old. It still has use but the attitude of backers can change year to year based on plenty of real world factors. An additional graph that might give some insight is a backer vs. goal graph. There you can see how the goal cost can drive the popularity of the campaign and can compare popularity of failed campaigns to successful campaigns.



# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

After careful analysis of previous Kickstarter ventures, there are several insights that we can arrive at. 
First, in the US Market, plays are one of the most successful ventures on kickstarter so this is good news for funding your play Fever.
![Category Outcomes chart](https://user-images.githubusercontent.com/103979048/170394447-e69f237e-8710-4798-baee-340883dbab7c.png)

## Timeline
Next, we should look at when to launch your campaign.

![Outcomes based on Launch Date](https://user-images.githubusercontent.com/103979048/170395412-5823e169-b8a6-435a-b234-d0cc6b997657.png)

For plays in the US market the month of February is the best option for launch with a relatively high amount of play campaigns succeeding along with some of the lowest numbers failing. If this cannot be managed, the highest amount of successful campaigns begin at the beginning of summer between May to June, however many play campaigns also fail, meaning there just may be a higher concentration of campaigns launched during this period. 
At all costs avoid launching in December as this is the least succesful time period to launch.

## Budget
As shown in the Descriptive Statistics sheet, your proposed budget of over $10k may be risky for your campaign. In fact, using the IQR rule we can determine that a successful campaign at $10k would be an outlier in this data. I would propose trying to cut down your budget to at most around $5k as that is still in the upper quarter of budgets that succeeded and closer to the average successful campaign.

## Overseas Musical

![GBMUSIC](https://user-images.githubusercontent.com/103979048/170397962-67a2520d-c478-4345-a563-c8f210f0ad1d.png)


Musical campaigns in Great Britain overall have failed more than they have succeeded. If you were to launch a campaign, it would be wise to launch with a maximum goal of $2k. 3/4 of the campaigns launched got less than $2k pledged so launching with any higher of a goal would be quite risky. Seeing as over a quarter of the campaigns never received a single pledge I would advise you to not attempt this project.
