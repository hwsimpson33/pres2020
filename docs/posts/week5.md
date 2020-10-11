## Federal grants and presidential campaigns
### October 3, 2020

[Back to main page](https://hwsimpson33.github.io/pres2020/)

This week, our dataset focused on advertising in presidential campaigns. A few weeks ago, I discovered the [Stanford Cable TV News Analyzer](https://tvnews.stanford.edu/) and I wanted to use this tool to compare TV news mentions of candidates and advertising spending. Political ads are designed to persuade voters, as [Huber and Arceneaux (2007)](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1540-5907.2007.00291.x) argue. But perhaps they also drive the political conversation, pushing narratives that are then picked up by political talk shows and end up reflected in voters' opinions. On the other hand, ads might respond to themes that already exist in the political environment, trying to shift the conversation in a direction that is more favorable to their candidate. 

This research project would be interesting and (I believe) viable, but it would require either automatically querying the Stanford TV Cable News Analyzer or running over 150 searches by hand to match the ad topic categories in our dataset. Unfortunately, I did not have time to do either this week. Instead, I picked a simpler research question: what is the relationship between mentions of candidates' names on cable TV (measured as the number of seconds someone is saying their name on TV), candidate ad spending, and polling averages? I combined day-by-day time series of these variables for the 2012 race, the only election for which I have both cable news data and ad data, and transformed each into a measure of advantage for the Democratic candidate by finding the percentage of TV mentions/ ad spending for Obama out of the two-party total.

<img src = "../images/time_plot.png">

[Click here to see full-size image.](https://hwsimpson33.github.io/pres2020/images/time_plot.png)

I started by calculating the correlation between each pair of variables. Ad advantage did not show much correlation at all to either poll lead or cable news advantage. Poll lead and cable news advantage, however, were signficantly negatively correlated (correlation = cor = -0.1523, p = .03357). This would suggest that, when Obama is ahead in the polls, he tends to be mentioned less on cable TV news relative to Romney. This result is suggestive, but does not take into account the time-series structure of the data. It treats each day as a single observation, and the observations are not ordered in relation to each other. 

In order to incoporate this information, I used a time-series method called Granger causality. 

Next, I ran a series of [Granger causality tests](https://en.wikipedia.org/wiki/Granger_causality) for each ordered pair of variables. Granger causality tests are used to determine if one time series can "predict" another, i.e. if changes in time series x happen before changes in time series y. Granger tests cannot be used to show causality per se, because a third variable could be driving changes in both x and y, there is no way to control for other relevant variables, and the correlation between the two variables could be spurious. The Granger test does show that there is some sort of relationship between the variables, however, and it is particularly useful in chicken-and-egg situations when causality could run in either direction (or both).

The only ordered pair of variables to show significant results was using Obama's news advantage to predict his poll advantage. The results were significant at every lag order I tried (if I understand it right, when a time series is autocorrelated or not stationary, using higher-order lags allows you to correct for any bias). I couldn't figure out how to get AIC and/or BIC (which, according to StackExchange, is how you are supposed to pick between different lag orders), so they are all shown below. All of them are significant, however, indicating that there is some sort of relationship here.

<table style="border-collapse:collapse;" class=table_4430 border=1>
<thead>
<tr>
  <th id="tableHTML_header_1">order</th>
  <th id="tableHTML_header_2">p.value</th>
</tr>
</thead>
<tbody>
<tr>
  <td id="tableHTML_column_1">1</td>
  <td id="tableHTML_column_2">0.0402</td>
</tr>
<tr>
  <td id="tableHTML_column_1">2</td>
  <td id="tableHTML_column_2">4e-04</td>
</tr>
<tr>
  <td id="tableHTML_column_1">3</td>
  <td id="tableHTML_column_2">0.0052</td>
</tr>
<tr>
  <td id="tableHTML_column_1">4</td>
  <td id="tableHTML_column_2">0.0031</td>
</tr>
<tr>
  <td id="tableHTML_column_1">5</td>
  <td id="tableHTML_column_2">0.005</td>
</tr>
</tbody>
</table>

Using poll advantage to predict news advantage did not give significant results, however. These results suggest that, in the 2012 election, the candidate who got more news coverage then did better in the polls, a reasonable result. Ads did not have a significant impact on either news coverage or polling. 

Another interesting result I discovered while preparing to run the Granger tests was that [all] x [three] z [time] series have highly negatively (significantly) autocorrelated residuals, meaning that they exhibit reversion to the mean (see my [Week 1] blog post). This is an interesting observation in its own right. Is there some process that drives polls, ad spending, and news mentions to be negative for a candidate one day and positive the next day? Although I do not believe this impacts the results of higher-order Granger tests, I am also not confident enough in my understanding of Granger tests to be sure!

I decided to take a closer look at the raw data for poll advantage and TV news advantage. There are a few interesting observations to be made about this graph. First, the massive surge in Obama's poll numbers in September seems to correspond to the convention bump that [Sides and Vavreck] describe in our reading from several weeks ago. Second, Obama actually receives less coverage

[let's look in more detail at the relationship b/t... present graph, tell a story based on sides + vavreck, speculate on why this relationship appears]

[future research projects: disaggregate candidates]