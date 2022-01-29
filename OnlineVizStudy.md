# Online Data Visualization Tools
In this exercise, we leveraged the OECD's record of general debt to GDP ratio for countries where data is readily available. The first two visualizations allow users to compare countries, either for a given year or across a 1995-2019 timespan.

## OECD Data
This bar chart represents the countries' debt as a percentage of their total GDP for the year 2017. The United State's standing is highlighted for easy comparison.
<br>
<iframe src="https://data.oecd.org/chart/6Bba" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Bba" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>

## Flourish
### Timeline Grid

<div class="flourish-embed flourish-chart" data-src="visualisation/8542254"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<br>

### Snapshot Map
Another way to understand nations' debt is to take a snapshot of a year (2017, as used for the OECD bar chart) and provide a chrolopleth map. In this visulization, countries that had a high debt-to-GDP ratios are shown in red. Countries that were not included in the dataset have been greyed out. Hover any country to see their debt-to-GDP ratio.
<br>
<div class="flourish-embed flourish-map" data-src="visualisation/8549130"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Discussion

When working with multi-category comparisons, it is important that the audience is provided a sufficiently clear chart that broadcasts the core idea quickly, while potentially allowing for further exploration. The OECD's original bar chart, which leverages uniform color with the exception of an accent, allows readers to immediately see how the highlighted country's debt ratio compares to other nations. By ordering the categories by the data values themselves - in this case by ascending debt ratio - makes it immediately clear which nations are performing best and worst on this metric. 


The Flourish timeline grid sacrifices some simplicity to provide much greater information. Instead of a snapshot, this visualization allows the audience to assess relative trjectories, answering questions like "has the debt ratio for this country improved or worsened?" The use of uniform color and axes provides quick comparison, but their focus can be on the shape of each nation's curve. Pop-ups that provide greater information, such as a specific country's ratio at any recorded period of time, allows for exploration and new insights other than what is initially provided. In comparison to the bar chart, this style can also leverage color to highlight a key area of interest, but is better suited to dashboards where one wants to convey an overall trend. 


I chose to include also a chrolopleth map because it leverages much of the strengths of a bar chart - clarity and best suited to comparison - but provides the data that makes regional and geographic trends immediately clear. With this organization and a single-color spectrum palette, readers can immediately see which regions have the highest debt ratios. This style does not work as well for identifying trends as a line grid, but would we use a year slicer instead of taking a one-year snapshot readers would be able to scroll through time to see how the ratios have changed on a global and regional level.
<br>

### Return to Portfolio

See more of my work at <a href="https://adorseyt.github.io/Dorsey-Tyler-Portfolio/">Alea Dorsey-Tyler's Portfolio</a>
