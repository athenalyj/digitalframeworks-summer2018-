# Assignment 7: Find a Story

Using either the FEC, Senate lobbying portal, congressional disclosure forms or White House disclosure forms, find a newsworthy story that hasn't been previously reported. This can be something of interest to a local or national news audience.

Write a pitch to your editor about how you would pursue this story. This may include what other sources you would check with, what further data analysis you may perform and how long the story might take you.


1. A step-by-step data diary of how you obtained the data and any cleaning/analysis you did
1. A sample headline and nut graf based on your finding


I found that during the 2016 presidential election cycle, a great number of Journalism school professors contributed to the two candidates, even though the [SPJ](https://www.spj.org/ethics-papers-politics.asp) specifies that journalists should not "get involved" or "contribute money" for political campaigns.

This is an intersting issue because technically journalism school professors are not journalists who should follow the SPJ codes. However, they teach future journalists with words and action. If they say donating to campaigns is unethical in class but donate money themselves, it might not be a good model for students. 
I would interview the SPJ Ethics Committee to see what a role journalism professors should play in this issue. I would also talk to professors who donated money and those who did not to get opinions from both sides. 
I would also like to check the former presidential election cycles to see if there is a trend that more journalism school professors are getting involved in political activities. 
This story would be finished in two days.   

In order to find my story, I did the following:

1. Searched the FEC website for donations in the 2016 election cycle from employees of "Journalism."
2. Filtered to only contributions to "Hillary For America" and "Donald J. Trump for President, Inc."and exported a CSV file of the results
3. For the CSV, I: 
    * took the sum of the `contribution_receipt_amount` column
    * made a pivot table to get the unique number of donors to each campaign

Hed: Clinton's Donors Far Outnumber Trump's At Northwestern

Nut graf: Last election cycle's split wasn't even close. The Hillary For America campaign committee reported to the Federal Election Commission receiving donations from nearly 270 employees at Northwestern. 

How many gave to Donald Trump? Eight.

