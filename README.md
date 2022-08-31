# An Analysis of Kickstarter Campaigns

## Overview of Project

### Purpose

After completing the previous series of analysis to help Louise, an up and coming playwright, plan her first campaign for her play, further analysis was conducted to determine if the outcome of campaigns are affected by either campaign goals, launch date, or both. The overall purpose of this analysis was to visualize outcomes based on launch date and funding goal amount and determine if either metric had an effect on theater campaign outcomes.
    
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To begin the analysis of outcomes based on launch date, a pivot table was first created to summarize the total number of successful, failed and canceled campaigns based on which month of the year the campaign was launched. The data used for the analysis was filtered to display the outcomes of only theater campaigns, as they were most relevant to Louise's campaign. A line chart was then used to visualize the correlaton between the number of successful, failed, and canceled campaigns based on the campaign's launch month. The visualization below displays an overall trend in the number of successful, failed, and cancelled outcomes depending on which month of the year the campaign was released. 

  ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/96188669/187731992-881f3cc5-3237-4031-8569-4e36074753ea.png)

    
### Analysis of Outcomes Based on Goals
The analysis of outcomes based on funding goals began with filtering the data to include only the campaign funding goals for plays. This was essential to maximize the accuracy of any relevant trends in campaign outcomes. Plays funding goals were then parsed into $5000 goal ranges, and a count of successful, canceled, or failed campaigns falling within each range was completed. A percentage calculation of each campaign outcome, either successful, failed, or cancelled was then executed, which was then visualized using a line chart. As there were no canceled campaigns that fell within the specified criteria, canceled campaigns are not present within the line chart. The visualization below displays an overall trend in the percentage of successful and failed theatre campaigns based on funding goal range.

![Theater_Outcomes_vs_Goals](https://user-images.githubusercontent.com/96188669/187732524-d40dc337-2307-45a7-b39e-0f896b9e3614.png)

   
### Challenges and Difficulties Encountered
One challenge that was encountered was the default inclusion of multiple items within the pivot chart Rows field. This was a situation that occured when creating a summary chart for the campaign outcomes based on launch date. When adding the variable 'Year' to the pivot table rows field, additional items, such as year and quarter, were automatically included. If this was not addressed, the resulting graph would display the count of campaign outcomes on a quarterly basis, which would not provide a visualization that is detailed enough to make an informed decision. Additional troubleshooting was required to edit this automatic inclusion, and display the Years field in months to increase the detail in the resulting graph.

## Results

### Outcomes Based on Launch Date
Based on the first analysis and visualization, most of the campaigns that were successful were launched in May (111 successful out of the 839 total successful launched), whereas the least amount of successful campaigns were launched in December (37 successful out of the 839 total succesful launched). The highest count of failed campaigns occured in July and October (50 failed for both months out of the 493 total failed launchd), while the highest number of canceled campaigns were in January (7 canceled out of the 37 total canceled), although the overall trend of canceled campaigns where relatively constant. Therefore, we can conclude that the best month to launch a campaign is in May and the worst month to launch a campaign is December.

### Outcomes based on Funding Goal
Based on the second analysis and visualization, close to 76% of campaigns were successful when their funding goals were less than $1000, the highest percentage than any other goal range, whereas 100% of campaigns failed when their funding goals were between $45,000 and $49,999. Campaign success and failure were equally chanced when the funding goal was between $15,000 and $19,999. Based on this information, we can conclude that the higher then campaign funding goal, the higher percentage of failed campaigns there will be. 

### Limitations to This Dataset
One limitation of this dataset is that the sample size is quite small. the total amount of observations in this dataset is 4114. With a dataset that is supposed to be representative of campaigns launched internationally over the span of a few years, the results drawn from this dataset may not be a good representation of the outcomes of millions of campaigns occuring each year. To navigate around this dataset, additional observations should be included.

Another limitation of this dataset is that the data may be considered outdated. Most of the campaigns occured between 6 and 9 years ago, so the overall outcomes can be significantly different if Louise is launching this campaign in 2022. Pop culture and other trends could have major shifts in what is considered popular for the present day. As a result, campaign outcomes can vary greatly from the timeframe this data was collected to now, as a result of shifting category and sub category popularity. To minimize this issue, a collection and analysis of more recent data (i.e data within the last 3 years) should be considered.

### Additional Analysis That Could be Conducted

Possible tables and graphs that we could create to gain insight to additional trends within the data include a graph that assesses the campaign outcome based on average donation. This can provide a benchmark for Louise to use to gauge if future campaigns are on track to be successful.

Another visualization that can be created is a graph comparing campaign outcomes to launch country. This could be helpful for Louise to determine which country she should launch future campaigns that will have the highest chance of being successful.
