# Analysis of Crowdfunded Kickstarter Campaigns
Examined, manipulated, and visualized 2015 Kickstarter data. Utilized filters, conditional formatting, PivotTables/PivotCharts, central tendancy measures, and various plotting techniques.

The purpose of this excersise was to determine specific factors that impact a campaign's likelihood of success.

## Filtering By Category 
![ParentCategoryOutcomes](https://user-images.githubusercontent.com/32782443/65636267-d4376780-df96-11e9-853d-dbac204b0aad.png)

![SubcategoryStatistics](https://user-images.githubusercontent.com/32782443/65636312-e3b6b080-df96-11e9-8878-980601ecb2ab.png)

![GBMusicalCampaigns](https://user-images.githubusercontent.com/32782443/65636802-e1088b00-df97-11e9-9dac-5bee47286710.png)

## Examining Launch Timing
![OutcomesBasedOnLaunchDate](https://user-images.githubusercontent.com/32782443/65636320-e74a3780-df96-11e9-8163-1e4f26fac923.png)

![OutcomesBasedOnDuration_Grouped](https://user-images.githubusercontent.com/32782443/65733219-7aac6700-e082-11e9-9b4d-0628b21eacfc.png)

Based on the analysis, there are multiple factors that have been identified as being correlated to a campaign's chance of success. When looking at campaigns falling into the category of "theater" out of the 3 subcategories "plays" is historically the most successful demonstrating the importance of how the campaign is listed. Projects launched between May and June showed higher success rates compared to projects launched in any other month. This highlights the importance of launch timing when considering starting a campaign on Kickstarter. The projects that lasted between 21-30 days are also the most likely to be successful based on this 2015 Kickstarter data compared to those spanning longer or shorter time periods. Therefore, there seems to be a "sweet spot" for the duration of a compaign.  
With all of these identified factors, there would be the highest chance of success for a theatrical campaign if it is in the subcategory of "plays", launches in May/June, and is live for 21-30 days.  

### Challenge
![OutcomesBasedOnGoal](https://user-images.githubusercontent.com/32782443/65721848-be41a980-e05f-11e9-8e40-3ce33eef4ea1.png)

When focusing on the 'goal' aspect of launching a Kickstarter campaign, there are clear ranges that prove to be more successful. Based on the above graph, it's clear that projects with goals in the range of $0 - $4999 have the highest chances of success. The data shows that to maximize the chances of a successful theatrical campaign the goal should be less than $4999 in addition to the previously stated conditions. 

![OutcomesBasedOnDuration](https://user-images.githubusercontent.com/32782443/65733222-8435cf00-e082-11e9-9eef-0534e7100c91.png)

In examining the duration of the campaigns in more detail, it becomes difficult to tell if duration has an effect on the outcome of the campaign. Further exploration into this would focus on the percentage of campaigns in each "duration group" to account for the vastly different number of campaigns in each bin. A graph of Percent of Total Campaigns vs. Duration would be interesting to see.

### Limitations
The data leaves some questions unanswered. For example, how does the marketing of the product impact the likelihood of success? This question is less quantitative than previous querries but it is still a significant aspect to the problem of maximizing the chance of success. Another limitation is the lack of a "time examined" column; the average amount of time spent looking at a campaign. This would be interesting to see if there is a correlation between time spent looking and chances for donating. Following up to this, knowing how many views each campaign had would enable the graph of Number of Views vs. Outcome as well as producing the percent of people who viewed the site and then backed the project. All of these questions are ones that seemingly would have a roll in determining the chances of success of a campaign but can not be answered with this data.
