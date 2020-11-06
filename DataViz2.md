# Data Visualization Project #1- General Government Debt
## OECD Data Version
<iframe src="https://data.oecd.org/chart/69sf" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/69sf" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>


Both of the following charts describe and contextualize various international **Debt-to-GDP ratios.** These ratios express **the gross debt of the general government as a percentage of GDP.** 

This ratio is a key indicator of governmental financial sustainability; a low ratio indicates high capacity to pay back debts without incurring more debt.


## Redesign #1
### Linear General Government Debt, Last 25 Years
Alphabetically organized by country code, the chart below compares year-to-year trends for each country's debt-to-GDP ratio.
<div class="flourish-embed flourish-chart" data-src="visualisation/4252865"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Redesign #2
### General Government Debt Trends in Consistent Reporters
The chart below is comprised of a subset of data from the above sample in which only the countries that reported data for each year between 2000 and 2018 are analyzed.
<div class="flourish-embed flourish-scatter" data-src="visualisation/4253468"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


## Discussion
While the original OECD Chart is a good way of understanding the debt-to-GDP ratios as they compare to each other for one specific year, it does not give much context for the ebbs and flows of this financial measure on its own. Redesign #1 addresses this concern by providing a comprehensive, linear display in which the viewer can easily see the year-over-year figures for each country in one place. I chose to display all countries on a 5x7 grid, which results in an even distribution of graphs, resulting in no negative space or "loner" graphs at the end of the collection of graphs. The unavoidable problem with this design is that, because the data has to be split between multiple lines, it is difficult to make a big-picture analysis of all countries together because our eyes find it difficult to compare lines that are not nearby. We can certainly see that JPN, GRC, and ESP end in high ratios, but the massive differences in even these most extreme final figures for these countries is lost on the viewer unless they scroll to the pop-up and compare the actual numerical data. Because of the scaling made to display all of this data in one place and the sheer amount of separate data that exists, the difference between the EST's 13.39 final figure and ESP's 117.33 is lost.


In order to account for the previous chart's inability to provide insight to compare countries across a period of time, I created the box and whisker plot displayed in Redesign #2. I began this visualization by re-examining the data set I had pulled for analysis in my first redesign. As you can note in the grid of charts visualization above, the data sets for each country are not the same. Some countries reported for the full 25 year period (1995-2019) whereas some only reported for a few years. In order to account for this failing and provide a meaningful cross-analysis of the debt-to-GDP ratios for the varying countries, I narrowed the data to only report on the countries for whom we have data for the years 2000-2018. I chose this subset because this was the largest sample of complete data; only 6 countries had to be excluded from this subset (CHL, COL, ISL, ISR, MEX, and TUR).

In this visualization, we can easily compare the different debt-to-GDP ratios on the *same scale*. Unlike in the grid of charts in Redesign #1, it is easy to compare a country's overall performance as it relates to other countries, with the added benefit of seeing the median debt-to-GDP ratio for those countries during the period of time sampled. It does not provide a linear year-over-year narrative as Redesign #1 does, which can get confusing in cases such as CHE's case where the "highest" dot on the grid is from 2002, whereas the "lowest" dot is in 2018. However, since the title and description of this redesign does not indicate it is *supposed* to give a year-over-year analysis and rather the general trends, this shortcoming is mitigated.
