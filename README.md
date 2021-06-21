# An Analysis of Kickstarter Campaigns

## Overview
After the play *"Fever"*, written by Louise, achieved much of it's Kickstarter fundraising goal in a relatively short timespan, Louise desired some analysis of what factors might be critical to the success of the fundraising around her future plays. We looked at a large dataset of over 4,000 Kickstarter campaigns across several categories, including theatre, and carefully examined what common factors are most important to the success of a Kickstarter campaign for a new play. We discovered two primary factors which we believe to be most critical. 

## Launch Date
One of the key areas we looked at was the starting date of each campaign, to look for trends among the successful campaigns and determine if the timeframe for a theatre campaign was important. We compared the success vs. the launch date for campaigns in the "plays" category against other kickstarter categories to confirm that there was a specific timeframe in which plays performed better. Here is what we found.

![Theatre_Outcomes_vs_Launch](https://github.com/coryknuth/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png?raw=true)

# Summer Fun for Theatre Fundraising
As the data in this chart indicates, the summer months, particularly May, have a large spike in the number of successful theatre campaigns compared to the rest of the year. This is not a trend that we found across all Kickstarter campaigns, it only reflected strongly in the theatre category. The only potential challenge with this conclusion is the size of our dataset at 1,393 theatre campaigns. With more data we could confirm this finding even more strongly. However, even with this current data, the May trend is quite strong. We firmly support the conclusion that May is the ideal starting month for a future campaign.

## Goal Amounts
The other critical factor we discovered for theatre campaigns is the amount of the fundraising goal for the campaign. We again compared trends among campaign goals with success rates, and compared these findings in and out of the theatre category. Here is what we found.

![Outcomes_vs_Goals](https://github.com/coryknuth/kickstarter-analysis/blob/main/resources/Theatre_Outcomes_vs_Launch.png?raw=true)

## The Ideal Goal
In looking at the data around the percent of campaigns which successfully achieved their campaign goal in the theatre category we found the point at which a campaign became more likely to fail than success is $5,000. One challenge in this data is that in the $35,000 to $45,000 range we found a pocket of successful campaigns. However, only 6 of these campaigns were in the "plays" subcategory, and half of those 6 were "staff picked" campaigns, which increases awareness dramatically around the campaign. This left us with only 3 non-staff picked campaigns that were successful in that goal range. There also doesn't appear, at least with the data we currently have, to be any other notable factors which made this very specific goal range more successful than not. Based on the other data, the ideal fundraising goal for a future campaign is $5,000 or less.

## Limitations and Further Analysis
There are two potential limitations with the dataset we used. The number of theatre campaigns in total, and the limited number of data categories for those campaigns. If we obtain more data, with more granular detail, we could likely find even more insights into what makes or breaks a theatre fundraising campaign. Another further analysis we could perform is were there specific types of plays, or subjects that the plays covered that were more or less successful? We could also potentially analyze some factors beyond purely quantitative data, such as how much people enjoyed the plays that they fundraised, and how that impacted their likelihood of supporting a future campaign using some machine learning analysis.

## Conclusions
In summary, we believe there are a few critical factors to maximize the chances of success for future fundraising campaigns for plays.

*The ideal starting date for the campaign would be in May or June.
*Late fall and Winter months should be avoided if at all possible, as we found the least amount of successful campaigns in Sep - Jan.
*The ideal goal amount for the campaign would not exceed $5,000, as the likelihood of success in this category falls after that point.

Following these guidelines will give your future plays the greatest chance of successfully reaching their fundraising goal, and making it all the way to the stage. Can't wait to enjoy all of the future performances!
