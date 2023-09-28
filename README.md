# NBA-Trends-Project

Overview

This project delves into the world of the National Basketball Association (NBA) to uncover insights about team performance, playoff appearances, and more. We'll be examining data derived from 538's Analysis of the Complete History Of The NBA, which includes the original data from Basketball Reference, as well as additional variables added by 538 for their analysis.

Data Subset

To keep things focused, we've narrowed our scope to just 5 teams and 10 key columns (plus one derived column, point_diff). This subset allows us to analyze the NBA data more efficiently.

Data Exploration

Task 1: Points Comparison
In the 2010 season, we want to compare the New York Knicks and the Brooklyn Nets in terms of points earned per game. We've created two series, knicks_pts_2010 and nets_pts_2010, representing the points scored by each team.

Task 2: Mean Difference
We calculated the difference in average points scored between the Knicks and the Nets in 2010, which resulted in a difference of approximately 9.73 points. This suggests a potential association between team (fran_id) and points scored (pts).

Task 3: Histograms
To get a deeper understanding, we visualized the distribution of points scored by the Knicks and the Nets in 2010 using overlapping histograms. The distributions indicate differences between the two teams.

Task 4: 2014 Comparison
We repeated the above analysis for the 2014 season, calculating the mean difference and visualizing the histograms. This comparison allows us to track changes in team performance over time.

Task 5: Boxplots
Moving forward, we examined the relationship between franchise (fran_id) and points scored per game in the 2010 season. We generated side-by-side boxplots, revealing differences in average scores among various teams.

Task 6: Home vs. Away
To investigate whether teams tend to win more games at home, we created a contingency table of game results (win/loss) and game locations (home/away). The table provides insights into the association between these variables.

Task 7: Proportions
We converted the frequency table into a table of proportions, making it easier to interpret. The proportions reveal patterns in game outcomes concerning location.

Task 8: Chi-Square Test
Using the contingency table, we performed a Chi-Square test to assess the association between game results and locations. The test indicates that there might be an association, though it's not conclusive.

Task 9: Win Probability
We explored whether teams with higher win probability forecasts tend to win games by larger margins. We calculated the covariance between forecasted win probability and point differential, offering insights into their relationship.

Task 10: Correlation
We went a step further to calculate the correlation between forecasted win probability and point differential. The correlation coefficient suggests a moderate association between these variables.

Task 11: Scatter Plot
To visualize the correlation, we created a scatter plot of forecasted win probability against point differential. The plot illustrates the relationship we've uncovered.

This project allows us to gain valuable insights into the NBA and its teams' performances. Feel free to adapt and extend these techniques for your own data analysis needs. If you have any questions or need assistance, don't hesitate to reach out. Happy analyzing!
