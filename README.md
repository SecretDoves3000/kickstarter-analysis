# An Analysis of Kickstarter Data for Theater Projects from 2009 to 2014

## Overview of Project

In this analysis, we look at kickstarter data from 2009-2014. The focus of the analysis is the success or failure of funding campaigns for theater projects based on their launch date and goals; this serves to provide context for planning the timing and goals of a potential crowdfunded play, allowing future projects to be executed with the greatest chance of success.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In our first step of analysis we created a pivot table of outcomes vs launch dates organized by month. 

(https://raw.githubusercontent.com/SecretDoves3000/kickstarter-analysis/main/resources/theater_projects_by_month.PNG)

From that chart we plotted the following line chart

(https://raw.githubusercontent.com/SecretDoves3000/kickstarter-analysis/main/resources/Theater_Outcomes_vs_Launch.png)

As we can see, there is a significant uptick in successful campaigns at the end of spring and beginning of summer. At the same time, the number of failed campaings is relatively stable month to month. This means that increased success in May is more than a simple increase in overall campaigns, and so we conclude that May is the ideal month to launch a theatre project on kickstarter. Moreover, we see that the worst time for a launch is the heart winter, in December and January, so even if a May start is not possible due to circumstance, a winter start should be avoided.

### Analysis of Outcomes Based on Goals

In our next step we looked at a pivot table of the success and failure of projects based on their funding goals. 

(https://raw.githubusercontent.com/SecretDoves3000/kickstarter-analysis/main/resources/campaign_outcomes_by_goal.PNG)

From here we plot another line chart.

(https://raw.githubusercontent.com/SecretDoves3000/kickstarter-analysis/main/resources/Outcomes_vs_Goals.png)

Unsurprisingly, the proportion of successful projects is higher the lower the funding goal is. We do see an unexpected uptick in the 35,000 dollar range, but we can safely conclude this is an anomaly since, as we see from the table, there are only 6 such projects over the entire five year span of this dataset. Most likely, one well established troupe uses kickstarter to consitently fund their more expensive productions, although to see exactly what this phenomenon is would require further investigation. As such, we recommend that any future budget be kept as low as possible within the parameters of the project.

### Challenges and Difficulties Encountered

The primary challenge with this analysis was interpreting the line chart of the outcomes based on roles. While we were able to extract some meaning, the line chart format is somewhat difficult to interpret based on the organization of the corresponding data. We are also working with data across multiple years, so there is a possibility that we are missing trends across that span of time which should be taken into account.

## Results

- From our analysis of outcomes based on launch date, we can conclude that the best time to launch a project is in may, and the worst time is in december.

- From our analysis of outcomes based on goals, we can conclude that the best strategy for successful funding is to keep the goals as low as is possible while still funding a version of the project. 

- This dataset only provides total funding data, so it is difficult to create a detailed funding plan such as targetting a wide range of smaller donations vs trying to secure a smaller amount of larger donors.

- For future analysis, we should consider making the success by goal chart a histogram, as well as looking at an outcomes vs average donations 
