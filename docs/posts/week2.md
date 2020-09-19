To be honest, I’m a little disappointed with the results of this week’s analysis. This is the week when we are supposed to begin building our prediction models using the most basic fundamental, the economy. I had a vision for the model I wanted to build: a multilevel model with both national- and state-level variables as predictors and state-level election results on the left-hand side. This model makes sense to me because state-level election results are fundamental to US presidential elections. The election is fought state-by-state and strategic decision-making, campaigning, and media messaging effects should show up primarily on the state level. At the same time, the election is a national phenomenon and national-level conditions should also be included.
Unfortunately, the results of this week’s analysis do not bode well for the idea that state-level predictors should be an important part of my model. I was unable to build a convincing model using state-level economic indicators (Extension 3). At the state, we have to use unemployment as an economic indicator, because state-level GDP data only goes back to 1997. I started out by regressing state-level support for the incumbent party’s presidential candidate on Q2 unemployment during the election year. These results were not encouraging – not a single state had a significant coefficient. [link to state_raw_ec_plot]
Then I tried year-on-year change in unemployment. Perhaps the absolute level of unemployment is too messy an indicator, but change in unemployment shows whether the economy is improving or worsening. The results were better, but still not as strong as I had hoped: only eleven states had significant coefficients.
[state_diff_ec_table]
[link to state_diff_ec_plot]

#Troubleshooting the model
In class, we replicated the well-known result that GDP can predict national-level popular vote reasonably well. What is going wrong in these models? Does the relationship between the economy and voting break down at the state level? Or is unemployment just a bad way to capture those aspects of economic performance that voters react to? 
First, I decided to test the relationship between unemployment and national-level election outcomes. 
[nat_unem_plot]

The regression line is practically flat and (of course) the coefficient is not statistically significant. This result supports the hypothesis that unemployment, unlike GDP, cannot be used to predict vote outcomes. Next, I decided to regress state-level election results on national-level GDP.

[nat_state_ec_table]
[link to nat_state_ec_plot]

This regression tests the effect of national-level economic conditions on voting in each state. [explanation]


Again, only eleven states have significant coefficients. Notably, five states appear both in this table and the table from the year-on-year state-level unemployment regression above: Connecticut, Colorado, Nevada, New Hampshire, and New Mexico. Three of these states (Colorado, Nevada, New Hampshire) are on FiveThirtyEight’s list of swing states (https://en.wikipedia.org/wiki/Swing_state), so it makes sense that they would be unusually sensitive to both the national- and state-level economic conditions. Other swing states make one list or the other (Ohio, Virginia, North Carolina, Pennsylvania, Florida, Michigan) or neither list (Iowa, Minnesota, Wisconsin). 
[not strong evidence, but indicates that…]

Conclusion: what this means for my multilevel model
