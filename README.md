# kickstarter-analysis

## Overview of Project

This is a two part analysis of the Kickstarter dataset 
    1) Theater outcomes based on launch date
    2) Play outcomes based on fundraising goals

The goal of this analysis is to help Louise better undertand 1) the relationship between funraising goals and outcomes for theater campaigns, as well as 2) the relationship between launch dates and outcomes. Louise can use this information to time launch dates better and to pinpoint optimal fundraising goals.  

### Analysis Method

This analysis was performed using Excel. I used the "Sort and Filter" setting and PivotTables to extract and organize the data I wanted to analyze. I used line graphs with markers to create a visual display of the data.

### Analysis of Outcomes Based on Launch Date

Outcomes are speparated into three categories: 
   
    Successful - Campaigns that met funding goal 
    Failed - Campaigns that did not meet funding goal
    Canceled - Canceled campaigns

Launch date marks the beginning of a campaign. For this analysis, I grouped launch dates by month.

The most notable feature is the sharp increase of successful compaigns in the month of May. Successful campaigns decreased gradually from May to December. 
Failed campaigns also peaked in May, but remained at that level until August. Failed campaigns dropped in September then returned to peak level in October then dropped again in November.
The number of canceled campaigns remained relativly constant throughout the year.

    ### Conclusions

May is the best month to launch theater campaigns because...
    1) May had the highest number of successful campaigns
    2) The difference between successful campaigns and failed compaigns also peaked in May

December is the worst month to launch theater campaigns because...
    1) December had the lowest number of successful campaigns
    2) The number of failed campaigns equaled the number of successful campaigns 


### Analysis of Outcomes Based on Goals

Outcomes for this analysis follow the same criteria as the outcomes in the "Outcomes Based on Launch Date" analysis.
"Goals" is the total amount of money that needs to be raised for a campaign.

Successful and failed campaigns have a strong negative correlation. There were not any canceled campaigns. Campaigns with a lower a fundraising goal are more likely to be successful. Campaigns with a higher fundraising goal are more likely to fail.

    ### Conclusions

Louise should keep fundraising goals below $45000. Campaigns with a fundraising goal above $45000 are significantly more likely to fail. 
    

###Limitations

We do not know what the expenses were for each campaign. If Louise's objective is to maximize profit, we would need to know this.

If I were to add more to this analysis, I would create a line graph displaying the percentage of successful, failed, and canceled campaigns for each subcategory. This would help Louise decide which subcategory she should focus on.

I would also find out how long each fundraising campaign lasted and then compare that to the number of successful, failed, and canceled campaigns. I suspect that campaigns with a shorter fundraising period have a lower success rate.


### Challenges and Difficulties Encountered

It took me a while to perform the COUNTIF() function for each cell. There is probably a way I could have done this faster. Also, there weren't any cancelled rows but COUNTIF() kept returning a non zero result when I ran the function in the cancelled column. I had to enter the zeros in manually.
