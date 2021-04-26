Deliverable 3, Written Analysis 

1. Overview of the project 

	The purpose of this research was to analyze the different outcomes based on launch date and funding goals. This will help Louise to better understand why some fundraising goals are met and why others are not. 


2. Analysis and Challenges 
	
	I first started my analysis by creating a pivot table in a new sheet in the Kickstarter worksheet called “Theater Outcomes by Launch Date”. The chart was filtered by Parent Category and Years so that we can look at all the Theater data and find out which Months have the most failed, successful, or canceled outcomes. Next I created a line graph to visually represent the pivot table. After analyzing the graph it is clear that there are more successful campaigns in April, May, and June than any other months. We can also notice that the number of failed campaigns remains somewhat constant throughout each month, with a peak in Oct/Nov. 

	Next, I analyzed the outcomes based on goals in a new sheet and found that over 70% of campaigns were successful if their goal was less than 1000. From this analysis we can infer that the lower the goal, the more attainable it is to achieve. 

	Some challenges that I faced were related to the formulas needed to populate the different cells. When calculating the number of successful, failed, and canceled projects I got stuck on how to use the COUNTIFS()function and needed to rewatch tutorials in order to understand. I was specifically stuck on how to add more criteria for the different Goal ranges. This is an example of one of my formulas that I used to see how many projects were successful where the goal was between $40,000 and $49,999 

=COUNTIFS(Kickstarter!D:D,">=40000",Kickstarter!F:F,"successful",Kickstarter!D:D,"<=44999", Kickstarter!F:F, "successful”)


3. Results 

	What are two conclusions you can draw about the Theater Outcomes by Launch Date?

	The two conclusions that I drew from the Theater Outcomes by Launch Date is that May is the best month fro achieving successful outcomes, and that December is the worst month for achieving successful campaigns. 


	What can you conclude about the Outcomes based on Goals?
		
	I can conclude that the lower the goal, the better chance you have at a successful outcome. Far less percentage of outcomes failed than succeeded when the foal was smaller. After the goal reached $40,000, failure was more common than success. 

	What are some limitations of this dataset?
	
	Some limitations with the data is that we are reviewing the total amount of projects and not taking into account the individual variables that each project faced when determining their outcome. 
	

	What are some other possible tables and/or graphs that we could create?

	We could add a column for reasoning which could help us to determine why projects succeed or fail. 