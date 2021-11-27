# Analysis of temperatures for viability of surf and ice cream shop on the Hawaiian island of Oahu 
The analysis uses temperature measurement data to identify temperature trends for the months of June and December on the Hawaiian island of Oahu to determine if a surf and ice cream shop in the area is a sustainable year-round business.

## Overview
This analysis filters temperature measurements on date data available in a sqlite database (the hawaii.sqlite database) to:
1. Determine summary temperature statistics for June
2. Determine summary temperature statistics for December
3. Provide a write up on the analysis

### Steps to meet objectives:
* Retrieve all the temperatures for the months of June and December 
* Convert those temperatures to lists
* Create a DataFrame for each of those lists
* Generate the summary statistics fo each

#### Software: Python, Pandas, SQLite, and SQLAlchemy

## Results
1. Retrieved June temps/summary statistics from the hawaii.sqlite database using Python, Pandas functions and methods, and SQLAlchemy
  
  A snapshot of the summary statistics for June are shown here:

![June image](/resources/june_temps.png)

2. Retrieved December temps/summary statistics from the hawaii.sqlite database using Python, Pandas functions and methods, and SQLAlchemy

  A snapshot of the summary statistics for December are shown here:

![December image](/resources/december_temps.png)

## Summary
The analysis shows that June and December are viable months for surfing and eating ice cream temperature wise. I would recommend looking at writing additional queries to gather the precipitation data for June and December to get an idea on how much rain each of the two months have as well.

# References
FiveThirtyEight style sheet: https://matplotlib.org/3.1.1/gallery/style_sheets/fivethirtyeight.html
magic methods: https://www.geeksforgeeks.org/dunder-magic-methods-python/
