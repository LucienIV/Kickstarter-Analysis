# Kickstarting with Excel

## Overview of Project

The purpose of this analysis is to analyze the outcomes of Kickstarter campaigns based on their launch dates and their funding goals. The goal in doing so is to arrive at a set of optimal conditions in terms of timing and funding for the launching of a Kickstarter for a play.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For this analysis a pivot table was created based on the original dataset. Filters were applied to limit the data for only Kickstarter projects that were in the category of Theater. Projects were sorted by month based on their Kickstarter launch date and then further sorted based on outcomes of Successful, Failed, and Canceled. A line chart was created based on the chart to visualize the derived data. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92831138/142481732-d1f1a82a-2ec0-4576-ab0e-3331497e81a2.png)


### Analysis of Outcomes Based on Goals

For this analysis a new spreadsheet was created to determine the success or failure of Kickstarter projects that were plays based on their funding goals. The values for the funding goals were divided into $5,000 increments, with categories for Less Than $1,000 and Greater Than $50,000 as the caps at each end of the scale and all other values between them, i.e. $1,000 to $4,999. The COUNTIFS function was used to determine the number of successful, failed, and canceled projects for each funding range. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92831138/142481751-85d6d930-881c-4fa5-8a72-3e61eab3161f.png)


### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
