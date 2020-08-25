My goals from team insights: 8/13/2020
Tammi: Explore, look at the data. What can you bring back to the team?
Asia: What metrics can be collected from the data to answer our inital questions? Cost, output, impact, etc
Gina: Come from curious. After looking at the data, what questions do you have?

8/14/2020
Used emissions API to discover and plot emissions trends over 10 years

8/15/2020
Tasked with gathering solar output data by state. Two API's required: Output data is given by station. 
Needed to find station lats and longs by state. Began with Colorado out of randomness. Was able to retrieve
station data and create a list of tuples to feed ouput API. Exceeded rate limit at 3:20. Need wait an hour.
Will try again later to gather state info for CO and then alter parameters for other states. need to rename
notebooks, my bad

8/16/2020
Looking at output data, realized that this output data is not what we are looking for.
Saved ipynb elsewhere in case we need it, but removed it from the repo. Working with data from eia
currently. Pushed a dataframe for renewable energy production by state over the last ten years. Will plot
later. Thought it would be useful when drawing conclusions about solar impact on emissions. 

8/17/2020
Gathered more data from eia about solar consumption by state dataframes and plots in eia.ipynb. Found solar production data in an excel file
on eia, formatted with pivot table and saved as csv. Loaded csv into Jupyter notebook. Will plot later. Did population data work today
spent a bunch of time hitting the API to make a dataframe, then found a csv with all the information already in there (oops).

8/18/2020 Group meet up, decided on comparing variable as they relate to emissions data to see which has the strongest correlation to 
air quality / amount of emissions. My branch will examine renewable energy production as it relates to emissions.

8/19/2020 Was able to neatly convert all data I needed from my API calls into csv files. Organized and plotted data and plotted linear regression.
I also experimented with colorbar. SUPER NEAT! Its extra but I like it. I need to consider other comparisons that can be made between these datasets.
Probably will do some more data collection for renewable consumption to see if that correlates better. So far, findings are that production
rates are not indicative of high or low emissions. Would also like to show a histogram of some sort and of course a statistical test. Working on it.

8/20/2020 Had class today, we decided to examine correlations overall and then hone in on states of interest. I also made a scatter plot for consumption.
That was all for today was tired from grandma's services :(

8/21/2020 Worked on linear regeressions. Realized I did my scatter plots backwards and fixed them.

8/22/2020 Class today, we worked together and put most of the presentation together. Made slides and decided on a flow. Also for continuity, I made a bar graph.
Made a basemap for emissions level, again extra but I really liked how it turned out! Might scrap it though because it doesnt go with my part. Thats all for today,
time to study for finals.

8/23/2020 Worked basemap into my part. The idea of comparing the percentage of renewable consumption to total energy consumptions crept up on me 
while i was making a grilled cheese sandwich. Had to do another API call to get the information for total energy consumption by  state and then calculate
the percentages. I made some pie charts for our states of interest to compare to the emissions basemap. it turned out okay in my opinion. Worked on 
slides for the presentation and did some edits to the presentation for continuity. 

8/24/2020 Met with the group and did run through of presentation. Worked with Gina and Asia to fix the master branch. 

8/25/2020 Wrote speaker notes for my slides. Met with group. Today's the day!
