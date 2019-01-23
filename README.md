# NFL_Data_Project
Tristan Chung
Nick McClellan
Janet Davis- CS220
7 December 2018
NFL Data Modeling Project

In our data modeling project we aimed to find if offense or defense in the NFL influenced overall team record more based on percentage of drives scored, and percentage of drives where scores were allowed. We did not want to only do our calculations on a single scope of data, so we also did our calculations on number of points scored and number of points allowed.

We performed calculations on our data by first finding the mean averages of offenses and defenses in the NFL, for both percentage of drives scored and against, and also number of points scored and against. Then for each team, we compared their offense and defense to the league averages, and looked at the whether the offense or the defense performed better in comparison to the league averages. After comparing, we tallied up the wins for teams whose offense performed better, and wins for teams whose defense performed better in order to determine whether offense or defense helped a team achieve more wins.
We created our data types with the plan to create individual teams with different statistics to put into one big list of all NFL teams so that we could easily iterate across all of them.

We wrote our functions using higher order programming in order to have less repetitiveness when calculating on both offense and defense, because they largely used very similar calculations. 

One limitation of this model is that we only look at one season, and only a couple different offensive and defensive statistics. The weakness that comes with only looking at one season, is that the sample size is smaller, so there may not be a consensus that offense or defense is better. The weakness that comes with only looking at the statistics that we chose to calculate on is that there are so many other offensive and defensive statistics available, and so the ones we chose may not show the entire big picture.

Through coding this project we learned how to construct complex data types, and also how to work higher order programming. We also learned how to be flexible with code, as we modded the foldr function to suite our needs. 

Overall, we believe this data modeling project was a success, and we see the potential for our model to be easily expanded to use all the different offensive and defensive statistics available to us.
