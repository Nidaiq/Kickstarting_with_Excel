# kickstarter-analysis
# Kickstarting with Excel

## Overview of Project

### Background

Louise is an up and coming playwriter who had launched a crowdfunding campaign for her play *Fever*.  She had an estimated a required budget of $10,000.  Louise is now close to ending her campaign and would like to evaluate how her campaign had performed against others.  Data was obtained for several other campaigns that could be grouped into 9 parent categories (categories) and further broken down to their respective subcategories.  It is important to note that a play is subcategorized into a category of theater.  This category and subcategory is essential for the analysis done for Louise. 

### Purpose
Purpose of this project was to know how crowdfunding campaign for Louise's play compared to crowdfunding campaigns for others in the same category (theater) and subcategory (play).

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For the purpose of this analysis the file Theater_ Outcomes_vs_Launch.png in the folder named resources would be used.  The analysis of the the outcomes based on launch date when filtered by theater shows that over 61% of the campaigns were successful followed by 36% that had failed.  It was also found that the rate of cancellations for plays were very low at approximately 3%. Launch dates in Summer months have a high probability of success, with the highest overall peak for success shown in the month of May.  The month of December had the lowest success outcome.  

### Analysis of Outcomes Based on Goals
For this analysis the Outcomes_vs_Goals.png file in the resources folder was used.  It was observed that campaign with goals of less than $1000 had the most percentage of success for plays, at 76%, followed by campaign with goals between $1000-$4999 at 73% success rate for plays.  Surprisingly, a percentage success of 67% was observed between goals of $35000 to less than $45000.

### Challenges and Difficulties Encountered
Since the data set was large it had to be further broken down.  This was done by separating the category and subcategory into separate columns.  This allowed for better filtering of the data set for a more in-depth analysis.

Another challenge encountered in the original data set was that campaign launch dates and end dates were in Unix Timestamped.  They were changed into the Readable Format by using the formula (((time in Unix/60)/60)/24)+DATE(1970,1,1). 

## Results

### Conclusions drawn about the Outcomes based on Launch Date
It can be concluded that for better success next time Louise should definitely aim at launching her campaign during the month of May.  If for any reason she cannot launch during May, preference should be given to June and July as well.  This could be indicative of good weather drawing out more audiences to attend the plays. Tourism could also be a factor for a better success rate of the theater industry during the summer months.

It can also be concluded that theater campaigns launched during December have approximately a 50% chance of failing.  This could be indicative of other festivities during the month of December and/or harsher weather in certain countries resulting in lower success for the theater industry.

### Conclusions drawn about the Outcomes based on Goals
It is concluded that smaller projects, a crowdfunding campaign $1000-$4999 would yield the most success, should Louise decide to do another play.  However, for projects with a larger budget needs, Louise should set the goal between $35000 - $45000.

### Limitations of this dataset
Different currencies were used to set goals in different countries.  Since the data for goals and pledges was not standardized in one currency, the data could potentially change the charts related to pledges and goals. 

Another limitation of the dataset is that it doesn't address the "why" component of the analysis.  "Why were some campaigns backed up and successful where as others weren't even if they were launched during the same time in the same country?".  This part would require more qualitative analysis rather than quantitative analysis. 

### Recommendations: Other possible tables and/or graphs
A subcategory filter could be added to the file, Theater_Outcomes_vs_Launch.png and the graph could be filtered by plays.  This could help Louise determine specifically the outcomes of plays by launch dates.

A table of outcomes by countries as well as count of outcomes by category and subcategories. A bar graph could be created to see the different parent categories faired in different countries. This could help Louise determine other countries that she can target should she decide to expand her project on an international level.

Another analysis could be run to see what the optimal timeframe is for a campaign to stay open inorder to be successful. This could help Louise determine next time how long she should keep her crowdfunding open for.
