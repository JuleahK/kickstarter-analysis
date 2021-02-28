#**An Analysis of Kickstarter Campaigns**

##Performing analysis on Kickstarter data to uncover trends of successful projects based on launch dates and goals

###This project provides a large data sample of various Kickstarter projects. These are failed or successful projects based on location, goal, launch date, run time, and the type of project being funded. The purpose of this analysis is to help Louise determine which projects for theater were successful and why by comparing the data to failed projects. These insights will help her create her own successful Kickstarter project.

##Analysis and Challenges

This analysis was completed by filtering out data relative to what Louise was interested in. Specifically, she was interested in the “theater” projects and when the most successful projects were launched. A data set was made filtering out theater projects and their launch dates throughout a year, and the outcomes of those projects. A similar data set was filtered using a more specific filter for “plays,” and their outcomes based on the goals set by each project.

###Analysis of Outcomes Based on Launch Date
![Outcomes Based On Launch Date](https://github.com/JuleahK/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png?raw=true)

###Analysis of Outcomes Based on Goals
![Outcomes vs Goals](https://github.com/JuleahK/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png?raw=true)

There were several hurdles that had to be overcome during this analysis. These challenges just came from the newness of Excel and its functions. Finding the correct parameters in formulas was the most common challenge encountered and research and class resources were used to overcome them. The dataset and instructions were straightforward easy to follow.

##Results

The “Theater Outcomes by Launch Date” data shows a trend for more successful projects during the months of May and June, trending down to December. Failed and successful projects seem to trend in the same pattern based on launch date. While successful projects spiked in May and June, both failed and successful projects trend up and down similarly throughout the year with the only exception being December (failed projects trend up here and successful projects trend down). It can be concluded that May and June are the best launch date months, while December is the worst launch date month.

From the “Outcomes Based on Goals” data, the highest percentage of successful projects come from the “less than 1000” and “1000 to 4999” brackets; conversely, the highest percentage of failed projects from the “45000 to 49999” bracket. From this it can be said that the most successful projects had a lower goal and were therefore able to reach that goal more easily, and the projects that set an exceedingly high goal had a more difficult time reaching that goal. At the “15000 to 19999” bracket, the success rate is about 50%. Based on this data, Louise should not set her goal above this bracket to favor a higher success rate.

One limitation of the dataset is the mix of currencies. While this would not affect the “outcomes,” to get the most accurate results regarding goals and outcomes, the data would need to be filtered by each country using its own currency to ensure the data is not skewed.

An additional dataset showing project length could be useful to Louise to know how long a project should last before it can be successful or failed. This could perhaps be in addition to the “launch date” dataset, showing both when to launch and for how long. It could also be useful to know how many donors each successful project had as well as the average donation to each successful project. She would then be able to approach a potential donor with a suggested amount to donate, which could increase her chances for both a donor and a successful project. 
