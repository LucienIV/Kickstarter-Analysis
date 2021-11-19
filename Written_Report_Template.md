# Kickstarting with Excel

## Overview of Project

The purpose of this analysis is to evaluate the outcomes of Kickstarter campaigns based on their launch dates and their funding goals. The goal in doing so is to arrive at a set of optimal conditions in terms of timing and funding for the launching of a Kickstarter for a play.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For this analysis a pivot table was created based on the original dataset. Filters were applied to limit the data for only Kickstarter projects that were in the category of Theater. Projects were sorted by month based on their Kickstarter launch date and then further sorted based on outcomes of Successful, Failed, and Canceled. A line chart was created based on the data to visalize it. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92831138/142481732-d1f1a82a-2ec0-4576-ab0e-3331497e81a2.png)


### Analysis of Outcomes Based on Goals

For this analysis a new spreadsheet was created to determine the success or failure of Kickstarter projects that were plays based on their funding goals. The values for the funding goals were divided into $5,000 increments, with categories for Less Than $1,000 and Greater Than $50,000 as the caps at each end of the scale and all other values between them, i.e. $1,000 to $4,999. The COUNTIFS function was used to determine the number of successful, failed, and canceled projects for each funding range. The total number of projects was then determined with the SUM function and then was used to determine the percentage of plays for each funding range that fell into each outcome category. This was then used to created a line chart to visually represent the data. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92831138/142481751-85d6d930-881c-4fa5-8a72-3e61eab3161f.png)


### Challenges and Difficulties Encountered

No challenges or difficulties were encountered in the course of this project. Possible challenges could have arrived had the data been charted in a different way due to a few outliers with excessively high funding goals. Utilization of line graphs allowed for a visual presentation that removed any issues that could be caused by outliers. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

One conclusion that can be drawn from this analysis is that a large number of successful projects were launched in May with similarly large amounts of success for thos launched in June and July. That range of three consecutive months in the summer has the highest success rate of any point in the year. Conversely, another conclusion is that the span of November, December, and January has the lowest rate of success based on launch date. December in particular has an almost equal number of successes and failures. Based on this data it is safe to recommend that any Kickstarters for plays are better launched in the summer, starting in May. 

- What can you conclude about the Outcomes based on Goals?

The results of this analysis would indicate that typically the projects with a lower goal have a higher rate of success than those with larger goals. One exception to this is the projects within the range of $35,000 to $45,000. Projects in that span had a markedly higher rate of success than almost any other projects except for those that had a goal of less than $5,000. Based on this data it could be recommended that a play Kickstarter not have an initial goal of greater than $5,000 unless such a budget is absolutely necessary or there is enough verifiable interest that a larger goal can reasonably be achieved. 

- What are some limitations of this dataset?

The initial dataset has several limitations. One limitation is that the data has no metric for representing how much initial interest there could have been in a project prior to its launch, though such a metric would be difficult to implement let alone measure. The data was successfully filtered down to Plays and Theater, but there is no classification for genre present. It is entirely possible that comedic plays have a higher rate of success than dramas, but with this dataset there is no way to discern this. It would be interesting in future research to look into projects that raised a significant amount more than their initial goal and see where those projects fit into the charts produced by this analysis. 

- What are some other possible tables and/or graphs that we could create?

A box and whisker plot for the fundraising goals of successful projects could be useful in determining the optimal goal for a new project as well as the upper and lower limits of what the project should strive to raise. The same could also be said for projects that did not reach their funding goals being utilized so that it can be inferred what fundraising goals should be avoided. 
