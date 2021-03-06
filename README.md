# Kickstarter-analysis


##overtview of project

###Purpose
To help Louise gain information and statistical data on how other thearter play campaigns performed in relation to their 
launch dates and funding goals, a crowdfunding Kickstarter dataset was analyzed.  Out of that analysis charts were created to visualize the outcomes based on launch 
date and funding goal.  The data showed the what the differences in the time of year and certain price range that funding made.  

###Analysis and Challenges
In order to do this, we must select, extract and filter crowdfunding Kickstarter worksheet to create a line graph chart based from several columns that will be generated from
selected data. The data included was the monetary goal of thearter play start-up campagins that needed to be funded.   The range of funding was broken down in to 13 different 
ranges, starting at less than $1000 and then in segements of $5000 after that. The max funding goal was set to greater than $50000.  From here we sorted the 
successful, failed and canceled campaigns and their respective percentages. In order to filter the data, the COUNTIFS() function was used to extract the ranges and criteria 
needed to each cell.  The number successful column only pulled successful play campaigns from the separate Kickstarter dataset, failed and canceled pulled the same respecitve 
data.  A percentage formula was used to divide the number of successful campaigns by the total number of projects.  This percentage was then selected for the Y-axis of the graph
and for the X-axis the range of funding was selected.  This was done to create a visualization of how the percentage changes over the range of funding accomplished.  

The other outcomes analyzed were the based on the launch date of each campaign.  This data was selected in a pivot table to filter through the parent category and years
in the main Kickstarter dataset.  The outcomes were listed in the columns and values.  The rows were to depict months of year. This pivot table would then yeild a pivot
chart that has a line graph with markers to show the individual value of the number successful, failed or canceled withing each month.  

###Challenges
Challenges involved with this analysis may occur during the selecting of the right data range into your function for the COUNTIFS() and even your pivot table.  If the entirety
of the data selected is not in the pivot table, some feilds (columns from Kickstarter dataset) may not be available for your pivot table to filter through.  For the COUNTIFS()
function the criteria and ranges of the data select must be precise, other wise data may not get pulled and the value may become incorrect, thereby effecting your chart. 

##Results
Conclusion drawn from the chart and table created in the Outcomes by launch date sheet were that more plays were successful in summer than in winter.  There is a substantial increase in number of successful thearter campaign launchs in May.  Then it gradually decreases to below 60 after October.  This can also be due to the fact that most campaigns are launch in the warmer months.  December had the fewest number of campaigns launched and success rate is near 50% for a campaign to launch at that time of year.

The outcomes based on goals provided interesting data showing that campaigns that had a smaller goal were more often successful.  Some campaigns with very large funding goals were also successful, however the success and failure rate was 50% of each other. 

Some limitations may have affected our data because parameters such as demographics and other details of the campaigns themselves were not in the data set.  Another way to analyze this data could be to create a chart that showed how much was pledged vs the goal and how many backers each campaign had.  This could be done with a another line chart based off of COUNTIFS() function to select and filter data.   



