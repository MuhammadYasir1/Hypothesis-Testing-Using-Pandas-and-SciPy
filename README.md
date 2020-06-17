# Hypothesis-Testing-Using-Pandas-and-SciPy
**Hypothesis: University towns have their mean housing prices less effected by recessions.**

### Definitions:

* A quarter is a specific three month period, Q1 is January through March, Q2 is April through June, Q3 is July through September, Q4 is October through December.
* A recession is defined as starting with two consecutive quarters of GDP decline, and ending with two consecutive quarters of GDP growth.
* A recession bottom is the quarter within a recession which had the lowest GDP.
* A university town is a city which has a high percentage of university students compared to the total population of the city.

###  The following data files were fetched for this project:

1. From the Zillow research data site there is housing data for the United States. In particular the datafile for all homes at a city level, City_Zhvi_AllHomes.csv, has median home sale prices at a fine grained level.

2. From the Wikipedia page on college towns is a list of university towns in the United States which has been copy and pasted into the file university_towns.txt.

3. From Bureau of Economic Analysis, US Department of Commerce, the GDP over time of the United States in current dollars in quarterly intervals, in the file gdplev.xls. For This Project Data Onwards of the year 2000 is considered.

### Method Used to test the Hypothesis:

* SciPy TTest on mean values
