Data Visualization by Harikrishna Golla
-----------------------------------------------

My aim in this project was to come up with one summarized data visualization that can explain the performance of players attributing to the given data.

To come up with this final(explanatory) chart, I have created a few exploratory charts that can explain trend of the performance before I finalize on which parameters I could use for the final chart. I have included these exploratory charts as well for reference.
The major observations from the exploratory charts are:
1) More homeruns are made by right-handed players. The number of right-handed players are also more than other category players.
2) Batting averages of players do not have bigger variance but Left handed players have slightly higher batting average followed by both and then right-handed players.
3) Though right-handed players have scored more home runs, their average is not the highest.

I have also considered the feedback provided in the discussion forum by fellow cohorts in refining my visualization and to arrive at the final visualization.

Feedback 1:
------------
1) No Title
2) Scroll bar present. Resize the chart.
3) What do L, R, B stand for?
4) Chart doesn't convey a message on performance of players.

Design Changes:
I have included the title.
Resized the chart to do away with scroll bar.
Expanded the category names.
Included average home runs to depict the performance.

Feedback 2:
------------
1) Expand R,L,B to proper labels
2) What does HR represent? Put the full label
3) Legend is missing 
4) Did you remove the data points with 0 as average score? 
5) Have you looked at the effect of other parameters such as height, weight etc.,

Design Changes:
I have included proper labels.
Included the legend.
I have removed the data points with 0 as average score.
I have created exploratory charts to check the effect of height and weight and used these observations to create the final chart.


The final chart (05_Performance_by_handedness_vs_Body_Type_Exclude_Zero_Avgs.html) depicts the base ball players performance considering their handedness and body type. It is clear from the chart that people with heavy body type have more average homeruns than people with moderate or lean body type.
I have taken the ratio of height & weight to simplify it to single variable and defined the body types as below based on the ratio values:

Ratio < 0.38					---	Heavy
Ratio between 0.38 and 0.44		---	Medium
Ratio > 0.44					---	Lean

Further, I can infer that left handed players have more average home runs than right hand or both handed players. 
But surprisingly, both-handed heavy players have more average runs than any other category player. This is an interesting finding.
To summarize, the top 3 ranked players are as below:
1) Both-handed heavy players
2) Left-handed heavy players
3) Right-handed heavy players

However since the batting average of left handed players is higher than Right or both handed players, we can say that Left-handed players are top performing when only handedness is taken into consideration.

When body type alone is taken into consideration, heavy players have higher average home runs.

If there is a situation where we need to make teams from a bigger group (eg. High school teams), learnings from this pattern can be applied in forming the teams.

---------------------------------------------------------------------------------------------------------------------------------
References:
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.axis#ticks
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart
http://dimplejs.org/examples_viewer.html?id=scatter_standard

