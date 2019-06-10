# Kickstarter-Campaign-Analysis-Excel
Over two billion dollars have been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the over 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Since getting funded on Kickstarter requires meeting or exceeding the project's initial goal, many organizations spend months looking through past projects in an attempt to discover some trick to finding success. This repository is designed to organize and analyze a database of four thousand past Kickstarter campaigns to try and uncover any hidden trends within the data.

This repository was made to showcase the analytical potential of the Microsoft Excel program. 

![Alt text](https://github.com/SamLingle/Kickstarter-Campaign-Analysis-Excel/blob/master/Excel%20Images/ExcelTable.PNG)
'''
* Used Conditional formatting to show a different color in the 'State' column for "sucessful", "Failed", "Canceled", or "Live" projects.
* Used a percentage formula to create a new 'Percent Funded' column. Added conditional formatting to show a gradient three color scale based on percentage funded. 
* Used a formula to split 'Category and Sub-Category' column into  'Category' and 'Sub-Category' columns for easier visualization.
* Created 'Average Donation' column to uncover how much each backer paind on average to a given project.
'''
![Alt text](https://github.com/SamLingle/Kickstarter-Campaign-Analysis-Excel/blob/master/Excel%20Images/CategoryPivotTable.PNG)
By using a pivot table to divide the data by project outcome and parent category we can more easily see that:
'''
* The theatre, music, and film & video parent categories showed the highest numbers of kickstarter campaigns and the highest success rates.
* By percentage the highest rates of failed campaigns come from the food, games, and publishing parent categories.
'''

![Alt text](https://github.com/SamLingle/Kickstarter-Campaign-Analysis-Excel/blob/master/Excel%20Images/GoalLineChart.PNG)
To explore success rates based on desired money goal I put together a line chart which shows:
'''
* Highest number of total projects were looking for funding between $1,000 and $4,999.
* There is a positive correlation between higher Goals and higher Failure and Canceled rates.
'''

![Alt text](https://github.com/SamLingle/Kickstarter-Campaign-Analysis-Excel/blob/master/Excel%20Images/LaunchDateChart.PNG)
I wanted to see if there was any corelation between time of the year the project was launched and project success rates. To do this I isolated launch month and outcomes and placed them into a line chart for easier visualzation. 
'''
* Successful campaigns show a spike in Febuary and May with a continual dip until September. Then reach their lowest point in December.
* Failed campaigns fall most sharply between January and Febuary, and between October and November. 
'''

# Conclusions
'''
* The best time to launch a campaign would be in the month of May.
* A campaign will have a higher chance of success if it falls into the category of theatre, music, or film & video.
* A campaign seeking a goal of between $1,000 and $4,999 has a higher liklihood of success.
'''

# Next Steps
For a better understanding of what Kickstarter campaign outcomes, looking into what country and region projects are being launched and funded from could be useful to look into. as well as adding in datasets from more recent years to conduct a longitudinal study of success rates over the years since the starting of Kickstarter.
