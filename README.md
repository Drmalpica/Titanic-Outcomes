Summary: 

This graphic shows the distribution of survivors and casualties of passengers aboard the Titanic. My goal was to highlight the disproportionate number of females among the survivors and males (particularly those of the third class) among those that did not survive. 

Design: 
I originally chose a stacked bar chart to best visualize the outcomes of each passenger on the Titanic, separated by 
passenger class.  Since gender greatly influenced whether a passenger survived, color was added to show the two genders
separately.  I chose red and blue as the colors for the gender as I felt these were intuitive color choices.  Additionally, I chose darker/ligher versions of each to differentiate between survivors and casualties because I wanted to maintain that intuitive color choice while also drawing focus on the casualties.  Finally, I added interactivity to the graphic so the reader could get a more detailed view of each group without muddling the overall graphic I wanted to display. 

The orignal graphic changed the bar sections to orange when you hovered over them.  After feedback from reddit said this was confusing and suggested I change the outline instead, I took their advice and implemented this change.  Other suggestions made from this same person suggested I use a tooltip rather than the infobox at the bottom of the graph to display the additional information that I wanted to display, but I couldn't quite get that to work, so I opted to leave it as is (with the infobox at the bottom). 

Some other feedback I received suggested I move the legend out to the side and to add a percent sign to the appropriate fields in my infobox, 
which I did. 

**Updates after first submission**
I followed the reviewers suggestions and made changes to my code to adhere to javascript syntax norms. Secondly, I added an intro
paragraph to the graphic to get the reader engaged.  I also made the chart a bit larger to make it more readable. Finally, the reviewer suggested I add some sort of conclusion to my chart, but with the infobox I was using, there just didn't seem to be enough room on the page.  I decided to revisit the tooltip suggestion to see if I could get it to work.  Once I got it successfully implemented, I removed the infobox and added the conclusion paragraph.



Feedback: 
1) From programmer friend: 
"This is very interesting. It seems like gender was the prevailing indicator of whether you survived or not.  From 
the movie, I would have thought passenger class mattered more.  Well I guess it did if you were male.   Good graphic."

2) From Reddit:
"Why choose under the chart legend versus tooltip (so I don't have to move my eyes while hovering)?

The highlight color changes so I can no longer see the classification color without reading the legend (maybe a border change instead of a fill change).

How did you choose your colors? (No wrong question here, but there's a lot of science behind color choices, so mention it more so you can look at alternatives). What would a color blind person see?"


3) From Reddit: 

"It looks a little small and I'll add that you could move the legend to the right of the figure. Unless it's necessary for space restriction reasons, I think that putting the legend directly on the chart area makes it harder to read.

Also, add a percentage sign in front of the values you give in the mouseover.

That all being said I think you did a good job using d3 :) The chart works - these are all just tweaks to make it a little more readable, so that anyone who is consuming it has to spend less time trying to understand what everything represents."

Resources: 
 
	Creating stacked bar chart
	http://curran.github.io/screencasts/splittingCharts/examples/viewer/#/17

	Adding axes labels
	http://www.d3noob.org/2012/12/adding-axis-labels-to-d3js-graph.html

	Creating a color legend-v3
	http://d3-legend-v3.susielu.com/

	Adding interactivity
	http://jonathansoma.com/tutorials/d3/hover-notes/
	
	Adding tooltips
	http://bl.ocks.org/Caged/6476579