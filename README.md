# ENGR-315-Final-Project

By Camden Lovings and Connor Gunnell

Objective and Motivation:
  To analyze data regarding Education, population, Poverty, and Unemployment to find relationships, correlations or other interesting phenomena.
  The team plans to utilize the County-Level Datasets provided by the Department of Agriculture. This data covers 4 files, which are planned to be combined in a list. This dataset lists data for education, poverty, unemployment and median household income, and population over 4 unique CSV files. The primary goal is to try and interpret the data and find potential correlations between the different files. To do this, we are planning to ask these 3 questions:
    1. What effect does population have on Education
    2. For Education, population, Poverty, and Unemployment Harrisonburg was there a time a dip or spike in one group was followed by a dip or spike in a different group.
    3. What are the periods of time that had major changes in population growth? What are some events in this time that might have been responsible?

Introduction/Context of project: 
  Within the dataset there are four sets of data, and each outlines different subjects. Each dataset comes with a note about the data. For example, the poverty data explains the number of people below the poverty line, and how it counts families combined as being in poverty. The education dataset comes with no notes but does show 49 different pieces of data for each county, from bachelors degrees, to high school graduation rates, to even less than a high school diploma, showing values by decade starting in 1970. The unemployment data shows civilian labor force, employed, and unemployed, as well the unemployment rate for each year from 2000-2023. Finally, the population dataset shows the census data, estimates of population in the years following the census, and the change factors, between births, deaths, domestic migration, and immigration. 

  Current Questions aiming to answer:

  What is the rate at which percentage of people with a bachelor's degree or higher, are there counties with a percentage 50% higher than average? Are there counties with 2x times the average?

  For Education, population, and unemployment in Harrisonburg, was there a time a dip or spike in one group was followed by a dip or spike in a different group.

  Does employment have an effect on high school or college graduation, do counties that have high employment have high high school and college graduations?

  
Implementation Details:
  Each Data set has a unique "Attribute" column as described above. These attributes separates the data by a specific attribute, ex. within the education data an attribute is "High school diploma only", each attribute is followed by a date. In order for the data to be processed each data set will need to be processed for each specific attribute utilizing .split functions to create separate data based on the year and attribute, the date was then located and stored with a 'for' loop. The .join function was used to recombine attributes without the date. 
  
  For the education dataset there was variation in the attribute description, an attribute error list an each unique attribute was entered. A processing function was created which used each unique attribute to filter and standardized each attribute. 
 
Results

Question one:
  Graph "Education_vs_Population"
  Average rate of Bachelors 23.82%
  Less than half the average: 818
  More than 50% the average: 76
  More than double the average: 9 ['35028', '36061', '51013', '51510', '51610', '6075', '8053', '8097', '8113']
  
Conclusions    
  Analyzing the Graph "Education_vs_Population", we can see that the percentage of individuals with a bachelors degree or higher is fairly consistent, however some outliers are present. After analyzing the data for outliers we found that there were over eight hundred counties that had less than half the national average, seventy six that where above the national average by 50% and nine with more than double. 
  The nine counties were Los Alamos County New Mexico, New York County (Manhattan) New York, Arlington County	Virginia, Alexandria City Virginia, Falls Church City Virginia, San Francisco County California, Hinsdale County Colorado, Pitkin County	Colorado, and San Miguel County Colorado.  Of interesting note is a third of the counties are in a Virginia and another third is in Colorado. 
    
References/Source files:
        U.S. Department of Agriculture, Economic Research Service. (2025, January 31). County-level data sets. https://www.ers.usda.gov/data-products/county-level-data-sets/documentation, Accessed October 21st, 2026.
