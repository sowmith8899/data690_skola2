# Assignment 07

This dataset was downloaded from the website http://www.worlddev.xyz. It contains four development indicators covering many years (earliest as in 1960 and latest as in 2021) and most countries from all over the world.

You are to explore the dataset and produce data visualizations using the following requirements:

- You must use Plotly/Plotly Express.
- Use this link to load the data https://raw.githubusercontent.com/wcj365/python-stats-dataviz/master/assignments/assignment_07_world_dev/world_devlopment_indicator.csv
- You must pick one indicator out of the four: population, life expectancy, GDP per capita, or suiside rate
- You must pick a few countries of your interest and compare them to see how they differ in the indicator 
  - Compare one year (pick the latest year) using bar chart, pie chart, and boxplot 
  - Compare all years using line chart
- You must compare all regions to see how they differ in the indicator 
  - Compare one year (pick the latest year) using bar chart, pie chart 
  - Compare all years using line chart
  - Note one: For population, you compare total, for the other three indicators, you compare the average. 
  - Note two: you need to use groupby method to get the sum or mean of a column for a group (here the group is region)
- Use all countries, and pick year 2020, make a scatter plot with x being GDP per Capita and y being Life Expentancy. This plot will tell you the relationship between wealth and health.
- Make sure you structure your notebooks and provide great format/style with Markdown cells, documdentations, and code comments.
