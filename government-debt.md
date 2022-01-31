# Visualizing Government Debt
January 30, 2022

## The data
The data used for this assignment was downloaded from the [OECD webpage](https://data.oecd.org/gga/general-government-debt.htm) and it contains the debt as percentage of GDP for OECD countries from 1995 to 2020. Here's a short description of the columns:

* `LOCATION`: String. OECD country using alpha-3 abbreviations.
* `TIME`: Integer. Year [1995-2020]
* `Value`: Float. Debt as % of GDP

Additionally, for the third graph, I included an additional column `Region` to create a grouping for the countries and have fewer colors. The region was taken from [this](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv) website. 

## Part 1. Working with web-based visualization tools
<iframe src="https://data.oecd.org/chart/6BmD" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6BmD" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>

## Part 2. Working with Flourish
The visualization below was made with [Flourish](https://flourish.studio) and shows the total debt as percentage of GDP by country and year. The data was downloaded from the [OECD webpage](https://data.oecd.org/gga/general-government-debt.htm).

<div class="flourish-embed flourish-chart" data-src="visualisation/8567505"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Part 3. Applying learned concepts

In general, the previous two visualizations made it difficult to get insights at a glance; Although simple, the first graph does not provide valuable information beyond the ordering of countries according to debt -which could also have been achieved using a table. Conversely, the second graph offers too much information to process and makes it difficult to make comparisons across countries.

I chose the slope chart to reveal trends that the audience may not have identified using the first two charts. Moreover, it condenses the data using a 5-year interval and highlights what I expect the audience to get from the visualization (using a different opacity for the countries I want them to ignore). Needless to say, the title already conveys the most relevant finding. Hence, the audience knows right away what they're looking at. 

> Insight: using a five-year interval, the visualization shows that the government debt (as % of GDP) for Japan and Greece has been consistently increasing when compared to other countries. 

<div class="flourish-embed flourish-slope" data-src="visualisation/8567663"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

[Go back to main page](/README.md)
