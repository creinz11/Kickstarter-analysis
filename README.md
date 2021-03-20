# An Analysis of Kickstarter Campaign Data

## Our Client launched a kickstarter campaign for her theatrical work, "Fever". Lousie came close to reaching her funding goal in a short period of time, but asked us to conduct  amore in-depth anlaysis relative to other kickstart campaigns both in the "Theater" category, and more broadly by funding goal.

## The purpose of this analysis to identify key trends of successful campaigns to optimize our kickstarter offering to successfully reach our funding goal.

## We conducted a wide variety of analysis based on different metrics including duration of campaign, funding goal, avg. pledge, time of year, category and subcategory. 

## The first area of our analysis was on the outcomes of campaigns based on a particular launch date. We identified 1,369 relevant data points, and segmented the data based on three outcomes; Successful, Failed, and Canceled. From this segmentation, we broke down our analysis further to look at the particular month a campaign was launched.  

## The second area of analysis we focused on was the goal funding amount relative to outcome. We conducted this analysis by initially segmenting the data into $5,000 funding bands based on the campaign outcome of Successful, Failed, or Cancelled. Based on this analysis, we calculated the the percantage of the a successful, failed, or canceled outcomes based on these funding bands.

## Results

For theater campaigns, we can deduce that April to July provide the highest liklihood of a successfully completed campaign based on our data sample. From September to November, we identified a spike in Failed campaigns, so we recommend staying away from initiating a campaign during this time span. December is the worst time of year to start a campaign based in the data Additionally, we recommend completing additional analysis to understand the root cause of this observation. [Theater_Outcomes_Vs_Launch](/Users/ChristopherReinhardt/Desktop/Vandy/Challenge 1/Resources/to/Theater_Outcomes_Vs_Launch)
Contribution guidelines for this project](docs/Theater_Outcomes_Vs_Launch).md)

In terms of campaign goal, campaigns within the following goal bands have the highest probability of being successful. ![Outcomes_Vs_Goals](/Users/ChristopherReinhardt/Desktop/Vandy/Challenge 1/Resources/to/Outcomes_Vs_Goals)
    
    1) Less than $1,000 - 71% successful
    2) $1000 to $4,999 - 66% successful
    3) $20,000 to $24,999 - 100% successful


    Note: This analysis is conducted across all campaign categories. Recommend conducting further analysis specific to the theater category in the future.

## Data Limitations and Challenges

While the analysis conducted provides indicative characteristic trends for successful campaigns, we run into a "correlation without causation" issue. While we can obectively identify the best times of year to start a campaign based on outcomes, or identify funding goals with the highest propensity for success, we do not have any underlying insight into what is driving these outcomes. The findings of this analysis could be enriched if we used our summary findings to dive deeper into a root-cause analysis. As a specific example, looking at December campaigns to understand why this time of year has the highest fail rate. Additionally, further qualitative/quantitative analysis on the actual donor behavior may be valuable to iunderstand what creates an engaging campaign based on average donation data.
