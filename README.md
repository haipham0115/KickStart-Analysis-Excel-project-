# KickStart-Analysis-Excel-project
Analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends
Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.

Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.

Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.

Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

Create a stacked column pivot chart that can be filtered by country based on the table you have created.

Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.

The dates stored within the deadline and launched_at columns use Unix timestamps. Fortunately for us, there is a formula that can be used to convert these timestamps to a normal date.

Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format.

Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.

Create a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

Now create a pivot chart line graph that visualizes this new table.

Create a report in Microsoft Word and answer the following questions.

Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create?

**BONUS ANALYSIS**
If one were to describe a successful crowdfunding campaign, most people would use the number of campaign backers as a metric of success. One of the most efficient ways that data scientists characterize a quantitative metric, such as the number of campaign backers, is by creating a summary statistics table.
For those looking for an additional challenge, you will evaluate the number of backers of successful and unsuccessful campaigns by creating your own summary statistics table.

Create a new worksheet in your workbook, and create a column each for the number of backers of successful campaigns and unsuccessful campaigns.

Use Excel to evaluate the following for successful campaigns, and then for unsuccessful campaigns:

The mean number of backers.
The median number of backers.
The minimum number of backers.
The maximum number of backers.
The variance of the number of backers.
The standard deviation of the number of backers.

Use your data to determine whether the mean or the median summarizes the data more meaningfully.

Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?



