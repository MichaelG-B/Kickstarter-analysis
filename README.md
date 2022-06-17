# Kickstarting with Excel

## Overview of Project
	
- This project was conducted since Louise, our client who we previously worked with when she was initially seeking fundraising for her play "Fever", has now obtained enough funds in a short enough time to develop "Fever". Now Louise wanted to learn more about successful campaigns in relation to their launch dates and funding goals, that way she has a better idea of when she should launch her campaign and what goal she should set for it. In order to provide Louise with this beneficial information, we will conduct a few analyses.

### Purpose

- The purpose of this analysis is to determine trends in successful campaigns via their launch date and campaign goals at launch. This will allow Louise to make important and crucial decisions around the development of her play "Fever". 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

- The purpose of this analysis was to visualize campaign outcomes based on launch date. For this analysis we first created a new column within our kickstarter worksheet titled "Year" which extracted the year the given campaign was created. We then created a pivot table from the kickstarter worksheet in a new worksheet titled "Theater Outcomes by Launch Data". We then used this pivot chart to specifically visualize all theater campaigns. This visualization helped us see how many were launched during each month, and how many were canceled, failed or successful based on that month as well as totals. We further clarified this by using the pivot chart to create a line graph as a more intuitive way to visualize the relationship between outcomes and launch month for Louise.

![Outcomes based on Launch date Graph Image](https://github.com/MichaelG-B/Kickstarter-analysis/blob/247f54ddc71b734870613c5cf00b34e988699a89/Theater_Outcomes_VS_Launch.png)

### Analysis of Outcomes Based on Goals

- The purpose for this analysis was to visualize the percentage of successful, failed, and canceled plays based on  the funding goal amount. For this analysis we created a new worksheet titled "Outcomes Based on Goals" in which we grouped the goal amounts of all the "plays" spread over 12 cells starting from <1000 to >50000 by intervals of 5000. Now based on those groupings we tallied the number of successful, failed, canceled placing the amount in a respective column as well a providing a total for the amount of campaigns in that group. Once these counts were conducted we then created columns for the percentage of the campaigns with that rows goals which were successful, failed, or canceled. We then used this chart to create a line graph visualizing outcomes based on the campaigns goal as a more intuitive way to show the relationship between the two variables for Louise.

![Outcomes Based on Goals Graph Image](https://github.com/MichaelG-B/Kickstarter-analysis/blob/247f54ddc71b734870613c5cf00b34e988699a89/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

- Of the challenges that I encountered during this analysis they mainly dealt with the second analysis as the coding for each column ( Number of Successful etc + Percentage Successful etc ) was somewhat complex and took me a few attempts to get it right. I overcame this by just continuing to think intuitively about the purpose of each and trying multiple variations. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	
	- One of the conclusions I can draw about the Outcomes based on Launch Date pivotchart/line graph is that the majority of the successful campaigns were launched in may. This means that Louise would most likely find similar success if she was to launch her campaign in may as well.
	
	- Another conclusion I can draw is that after may the success rate steadily drops whereas the failure rate basically stays around the same rate. This means that Louise would have increasing chances of failure if she was to launch her campaign after may.

- What can you conclude about the Outcomes based on Goals?
	
	- One of the conclusions I can draw about the Outcomes Based on Goals chart/line graph is that between the goals of <1000 and 25000<=29999 there seems to be a steady decrease in success rate. This means that it would be wise for Louise to either have her goal as minimal as possible or have a goal outside of this range; a goal 29999<.
	
	- Another conclusion I can draw is that there seems to be a near perfect success rate for campaigns with a goal 45000< and <=49999. This means that it would be optimal for Louise to have a goal within this range.

- What are some limitations of this dataset?
	
	- Some of the limitations for this dataset include that range of information based on the year. The dataset only goes as far back as 2009 and only as recent as 2017, meaning we only have information based on the past 8 years. This could flaw our analysis by not showing greater trends, due to our narrow scope.
	- Another limitation could the variance between countries. Some countries due to their society may favor certain parent categories over others. This means that there is a certain layer of bias to our findings because peoples taste could also be impacted but the state of the society they live in as well, which would affect what they favor at a given time.

- What are some other possible tables and/or graphs that we could create?
	
	- I think a very beneficial graph that we could include based on the dataset is one that compares the number of backers to goal or even number of backers to outcome. In a sense I could imagine that focusing on obtaining many backers that support a little or few backers who support a lot could influence the success rate of a campaign.
