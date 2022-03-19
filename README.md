# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter campaigns and data to see trends in relation to goals, pledged amount, campaign run times, and location.

## **Overview of Project**

### Purpose
	To aid in creating a successful Kickstarter campaign, analysis of 4,000 existing campaigns was done. 
Previous analysis of data showed that theater and play category campaigns were often successful on the platform. 
With this information, Louise requested additional data on what details would likely result in success of a person campaign.
Relationship between success, fail, or cancelation rate and launch date, goals, and category were analyzed.
This allowed visualization of what would be the best criteria for future campaigns that would be successful.
Focus was applied to US theater or play campaigns to align with Louise's goals of starting a similar Kickstarter. 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Analysis and Challenges**

### Analysis of Outcomes Based on Launch Date
	To see relation of existing campaigns outcomes based on the launch date, a pivot table was created with those perameters.  The number of successful, failed, and canceled campaigns were totaled for each month. The data was filtered to display only theater category campaigns, to align with Louise's personal campaign type. A line graph was then created to allow ease of visualization of outcome versus launch date.  

![Screenshot_Theater_Outcomes_sheet](https://user-images.githubusercontent.com/100040705/159133276-25fd5266-f939-49a8-a70c-b32c6c47f22d.png)
----

### Analysis of Outcomes Based on Goals
	The relationship between outcomes and goal amount for plays was analyzed to determine starting goal ranges that historically exhibit success. The number of successful, failed, and canceled US play category projects were counted in 11 goal ranges from $1,000 to $50,000 were totaled. This information was then used to find the percentage of each outcome for each goal range. The results were graphed to depict the goal ranges with the most success. 

![Screenshot_Outcomes_Goals_Sheet](https://user-images.githubusercontent.com/100040705/159133268-f5d6f844-db55-4a13-8760-f111a1939f64.png)
-----

### Challenges and Difficulties Encountered
	Within the outcomes based on goals analysis challenges were incountered with formatting of the CountIf function for the number of campaigns in each outcome category. I found the sequence of criteria difficult to incorporate with the goal ranges and had to watch the informational video a few times before I returned accurate results. My original graph looked vastly different and would have given inaccurate results. Once I had reviewed my formula and module information, I was able to input the correct formula and therefore accurate data.

	Potential difficulties with outcomes by launch date include formatting the pivot table. Arrangement of pivot table field to get the most clear display of information may be a challenge, as well as formatting the years axis category to only show months.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Results**

Outcomes based on Launch Date:

  From the graph, we can gather that the most theater campaigns are launched in from April - August, with May being the highest total and successful campaigns for the year. Therefore, Louise has the best opertunity of creating a successful theater kickstarter if she launches in May. Additionally, the highest number of failed campaigns occur in October. Therefore Louise should not launch in October as there is a high rate of failure. 
  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100040705/159133016-ceec1901-c399-4c72-9879-be0e7f427b1c.png)
--------

Outcomes based on Goals:

  Based on the outcomes based on goals graph, the majority of US play projects had goals of under $10,000 (84%), with 51% of campaigns in the $1,000 to $5,000 range.  Projects in ranges under $20,000 had a success rate of 50% or more. Projects with goals between $35,000 and $45,000 similarly had high success rates (67%). If Louise's campaign has similar goals, she has a high chance of success. Since the lower range has significantly more total successful campaigns, Louise has a better chance of being successful if her goal amount is in this range. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100040705/159133025-faeeda64-be7a-4eb1-87aa-2f7aee74b628.png)
------------------------------

Limitations:

	Limitiations of the dataset include small sample size of theater or play categories respectively. A larger sample size could be obtained by obtaining further records from kickstarter. There may also be different outcomes for other crowd funding sites, examining exclusively kickstarter data may additionally skew results and other site data should be explored to examine larger trends. Outliers from campaigns that have been miscategorized or that are for large scale projects such as building theaters may have an effect on results.


	An additional graph could be created to show the total number of successful campaigns in a goal range in relation to the total overall number of play campaigns.  I did some simple calculations to see that the majority of campaigns have goals under $10,000. Since there are significantly less total campaigns in the higher goal parameters, there may be an additional relationship between goal amount and the chance of having a successful campaign. Additional pivot table and graph could be created to closer examine the launch dates in the most successful range (April to August) to see what other factors could lead to success.  Pivot tables could also be created to show the effect on campaigns of being a staff pick, or the length of time between launch and deadline of the project.
