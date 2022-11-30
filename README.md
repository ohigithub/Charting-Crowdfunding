# Charting Crowdfunding

## Description
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since they began in the late aughts, but not every project has found success. 
Getting funded on a crowdfunding website requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this assignment, I organized and analyzed a database of 1,000 generated sample projects in order to uncover trends indicating success or failure.

## Data Analysis & Findings

### Data Overview
I used conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live and create a new column called Percent Funded that uses a formula to uncover how much money a campaign made relative to its initial goal.

From there, I again used conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale begins at 0 at dark shade of red, transitioning to green at 100, and blue at 200. 

Additionally, I added 3 categories:
* Average Donation 
* Parent Category
* Sub-Category. 

This uncovers how much each project backer paid on average.
<img src="https://user-images.githubusercontent.com/102936852/204906558-6d941dde-23ed-448c-9c3b-7443a701ee3a.png">

### Success as Categorized by Parent Category
<img src="https://user-images.githubusercontent.com/102936852/204907364-bf3b6528-485c-4424-b090-c2a726da80b4.png">
This indicates that Journalism is the most conservative fundraiser as no one failed their goal who used that approach. Plays are most popular fundraiser subcategory within the data set. They both the single most high risk, yet high reward fundraising strategy as they had the most failures as well as success.

### Success as Categorized by Sub-Category
<img src="https://user-images.githubusercontent.com/102936852/204907432-29b19f2a-6048-4706-a5df-4b0a4f841342.png">
Science fiction and mobile games are undoubtedly the most unsuccessful fundraising endeavors.

### Campaign Success Overall
<img src="https://user-images.githubusercontent.com/102936852/204907477-f06f0e30-4a70-4d2b-bf37-e17a9dcbe499.png">
Fortunately, most campaigns succeed. It's worth noting that the highest amount of success is over summer with campaigns ending before August.

## Dataset Limitations
There is not insight into what factors contributed to the successes, failures, and cancelations of each fundraiser (e.g., startup costs, amount of time and people organizing the fundraiser, how it was marketed, etc.) Given that insight, this data set would be much more helpful to those organizing prospective fundraising projects. The highest success rate of fundraising projects ended by late summer. Given that the sample is spread across several years, it would be worthwhile to know what seasonal factors contribute to these successes to determine what other countries and how many industries can replicate the success.
## License
Trilogy Education Services, LLC.
