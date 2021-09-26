# Analysis Results for Kickstarter Campaigns

## Overview of Project

### Purpose
Louise has come close to being successful in her campign fundraising goal and di this in a short amount of time.  Louise wants to understand if the campaign launch date and their funding goals have any relation to an outcome of the campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The data available for us to complete an analysis for Louise has more information than what we really need.  Therefore, the first step in our process was to filter our data so that we are only looking at the information most relevant to our project.Since Louise is interested in the theatre category, we filtered our information to only include theatre.
Next, because Louise is interested in knowing outcomes based on launch dates, we created a chart to visualize the results:
    INSERT "THEATRE OUTCOMES BASED ON LUANCH DATE" HERE

### Analysis of Outcomes Based on Goals
Our next analysis focused on outcomes based on goals set for the campaigns.  We specifically want to to understand the percentage of successful, failed, and canceled based on the funding goal amount.

Dollar-amount ranges for the goals were created and a function was used to populate the number of outcomes that fall within those ranges.  Since Louise is especially interested in the "plays" subcategory of teh theatre category, the function only brought results if the subcategory was "play". From these results, we were able to calcuate the percentage of each outcome based on the goal amount.
INSERT "OUTCOMES BASED ON GOAL" HERE

### Challenges and Difficulties Encountered
A possible challenge that could be encountered in this analysis is found in the creation of the pivot table for the "Outcomes Based on Launch Date." We created a specific column and used a function so that we would only see the "years." When we create the pivot table, it is important to not use the years for the rows but to use the "date created conversion" so that the month would be included for our analysis. Using only the years would not have given us the information that Louise was looking for.

## Results

### Conclusions drawn about Outcomes based on Launch Date
1. The most successful theatre campagin outcomes occurred during the months of May, June and July with May being the most successful.  Therefore, we conclude that launching a campaign during these months would give Louise a higher chance of being successful.
2. The mean and median of failed outcomes are very close together indiciating a balanced data set.  Based on this information, there is not a month that has a significantly higher or lower failure count than another.  Therefore, we conclude that using the data for the successful campaigns would be a better indicator to choose when to launch a campaign.

### Conclusion drawn about Outcomes based on Goals
1. The most successful projects occurred in those with goals of $10,000 or less. As the goals increased the success rate decreased, until reaching the $35,000 goal.  There are significantly less projects with goals of $35,000 or higher.  Based on the review, we would conclude that having a goal of $10,000 or less for a campaign will give Louise a greater liklihood of success.

### Limitations of Dataset
1. The dataset only goes through the year 2017.  Although having data from 2009 to 2017 gives a wide range of data, having more recent data could enhance our analysis and give us more up to date results.
2. The currency adds limitation to our dataset. Although there is a column indicating the type of currency, it is not clear in the data that the goal and pledged columns have been converted to standard for comparison. Therefore, when looking at our results, they are probably not exact.

### Other Possible Graphs to be Created
1. We could create a graph for ourcoems based on country.  This woudl give us insight into certain categories or subcategories and their outcome based on the location of the campaign and would help Louise determine the best place to launch her campaign.
2. We could create a graph for outcomes based on if the campaign was a "spotlight" campaign or not.  This could help Louise determine if she should spotlight her own campaign.
