# Chicago Crime (Stuart Brown, Damien Crim, Jacob Dolinsky, Griffin Racey)
Project 1 - Chicago Crime
Overall statistical analyses of top three categories including location, month/year (Griffin)
What categories of crime exhibited the greatest increase before/after Covid? (Jacob)
What categories had the greatest decrease before/after Covid? (Damien)
Which month generally has the most MOTOR VEHICLE THEFT? (Regress on time of year) (Stuart)


# Data Source 
Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. In order to protect the privacy of crime victims, addresses are shown at the block level only and specific locations are not identified. This data includes unverified reports supplied to the Police Department. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error.


This is a large file. Do not add it to the repository. Create a folder called data in your local repository. Download the file 'chicago_crime_2019_2023.csv' from [here](https://drive.google.com/file/d/1kHz4It2UcT_4xua4mc9TIvk_XAHEQYFu/view?usp=drive_link) and add it to the 'data' folder. This folder is going to be ignored by git.

Tuesday, October 17: Have overall analysis finished, then begin individual year breakdowns; determine best graphs for respective questions' data

Thursday, October 19: Meet and discuss preliminary findings and analysis

Monday, October 23: Put everything together

Dataset Source: City of Chicago

Category: Chicago, Public Safety

## Choropleth Map Discussion

We wanted to show this visualization of the different community areas in Chicago to show that there are many factors to consider when looking at crime data. Many times we just look at the overall numbers but they don't always take into account factors like where you are in the city, the time of day, and time of year. This map shows that different areas of the city can vary greatly in the amount of crime they experience. The community area with the most amount of crime is Austin with 61,169 crimes in our dataset, and the area with the least was Edison Park with 1,284. We would have preferred to use crime rate (per capita) but I was not able to find reliable and recent data for population by community area. 

## Correlation Discussion

There seems to be a moderate linear positive relationship between the average monthly temperature and the monthly total count of crimes. The r value and the scatter plot both indicate this. This seems to make sense as it gets warmer, I would think people are more likely to be out and drinking. The summer months are warmer but also high school and college students would be out of school so that may contribute as well.

## Hypothesis testing for correlation - T-test

$H_{o}$: There is not a linear relationship between average monthly temperature and monthly crime total. 

$H_{a}$: There is a linear relationship between average monthly temperature and monthly crime total. 

p-val = .0000385

Since our p-value is less than 0.05, we can reject the null hypothesis. There is sufficient evidence that there is a linear relationship between the average monthly temperature and monthly crime total.
