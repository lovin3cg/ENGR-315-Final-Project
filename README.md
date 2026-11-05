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
  Does Population have a correlation with poverty on a county level?
  For Education, population, and unemployment in  Harrisonburg, was there a time a dip or spike in one group was followed by a dip or spike in a different group?
  What are the periods of time that had major changes in population growth? What are some events in this time that might have been responsible?

Implementation Details:
  Each Data set has a unique "Attribute" column as described above. These attributes separates the data by a specific attribute, ex. within the education data an attribute is "High school diploma only", each attribute is followed by a date. In order for the data to be processed each data set will need to be processed for each specific attribute utilizing .split functions to create separate data based on the year and attribute, the date was then located and stored with a 'for' loop. The .join function was used to recombine attributes without the date. 
  
  For the education dataset there was variation in the attribute description, an attribute error list an each unique attribute was entered. A processing function was created which used each unique attribute to filter and standardized each attribute. 
 
Results

Conclusions    
    
References/Source files:
        U.S. Department of Agriculture, Economic Research Service. (2025, January 31). County-level data sets. https://www.ers.usda.gov/data-products/county-level-data-sets/documentation, Accessed October 21st, 2026.
