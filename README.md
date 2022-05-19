# Kickstarter-Analysis
Performing an analysis on kickstarter data to uncover trends

## Overview and Purpose of Project
Louise, an up-and-coming playwright, wants helps starting a crowdfunding campaign to fund her play, FEVER. Louise is projecting a production cost of $12,000 and needs help determining the most favorable trends that would see her theater funding campaign to full fruition. With this analysis she can compare, assess, and infer analogous kickstarter outcomes to point her in the right direction of likely funding success.

### Analysis and Challenges 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105556091/169189670-53bf14d4-d09e-4875-b9e9-e2e4703acfae.png) The first analysis, Outcomes based on Launch Date, was abstracted based on _when_ the crowdfunding campaigns beganed. 
I created a Pivot table and chart of outcomes: Successful, Failed, and Canceled, 
https://1drv.ms/x/s!AsJ6yc5dsm1PlWc3Jc2aDZtQIJ_7 in correlation to what month the funding campaigns, for productions in the _Theater_ category, were launched. This way, Louise could evaluate the more successful periods of the year to initiate a crowdfunding campaign for a production in the same Category. The second analysis, Theater Outcomes Based on Goals, ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/105556091/169187284-050ea98c-0bd6-42f3-b3a7-a95d33a3f801.png)
was filtered with a more specific comparison to the other _Plays_ in the Category Theater. These outcomes were based on projected production costs. In this anaylsis the Outcomes: Successful, Failed, and Canceled were charted as percentages for statistical comparison of funding objectives, where Louise could get a better understanding of the level of proposal she's requesting and being able to asses how amounts correlate to campaing outcomes. 
Challenges That were faced during the analysis were few but surely encountered. Precisely, producing long, detailed formulas like COUNTIFS was definitely an obstacle that required a excessive amount of attention to detail. I had to repeated review the formula to make sure the appropriate filters were indicated, the proper punctuation for the arguments were present, and the math functions were grammatically correct.

#### Results

- Theater Outcomes Based on Launch date analysis indicated that the summer months is the most popular period of the year to initiate a campaign with a direct correlation to successful campaign funding-With the month of May being the most endorsed.

- Canceled campaign outcomes are neglible for 2 reasons, the relatively low number of canceled outcomes to the total number of campaigns launched throughout the year. and the lack of data on the justification behind campaigns being canceled.

- From Outcomes Based on Goals analysis it could be safe to say Louise's $12000 crowdfunding budget's success has an approxmiate 50/50 statistical outcome based on the data within that goal bracket.

Some of the Limitations of the database would be the missing information behind why some of the production's crowdfunding campaigns were canceled. That information could better help Louise prepare for her play's campaign as well as evaluate how many productions ran into those particular issues that affected the production's crowdfunding outcome. Another limitation is not charting the specific genres. Majority of the Theater/Play successful outcomes could be dominated by 2 particular genres that Louise's play, Fever, doesn't fall into.  And, a pertinent limitation of the dataset is not knowing who the producers  are of the play productions and how they correlate to the outcomes of their crowdfunding campaigns. 
Another table we could have produce would've been a Pivot table of the Outcomes based on the Length of the campaigns, or a Pivot table of Outcomes based on Subecategory by country.
