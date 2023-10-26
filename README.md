# Chicago Crime 
Project 1 - Chicago Crime
Overall statistical analyses of top three categories including location, month/year (Griffin)
What categories of crime exhibited the greatest increase before/after Covid? (Jacob)
What categories had the greatest decrease before/after Covid? (Damien)
Which month generally has the most MOTOR VEHICLE THEFT? (Regress on time of year) (Stuart)

## Group Members 
* Stuart Brown
* Damien Crim
* Jacob Dolinsky
* Griffin Racey

## Data Source 
Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. In order to protect the privacy of crime victims, addresses are shown at the block level only and specific locations are not identified. This data includes unverified reports supplied to the Police Department. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error.

MEAN MVTs per month:

January: 821.25

February: 725

March: 801.5

April: 785.75

May: 842.5

June: 884.75

July: 1110.75

August: 1215.25

September: 1256.5

October: 1517.5

November: 1412

December: 1373.5

## Choropleth Map Discussion

We wanted to show this visualization of the different community areas in Chicago to show that there are many factors to consider when looking at crime data. Many times we just look at the overall numbers but they don't always take into account factors like where you are in the city, the time of day, and time of year. This map shows that different areas of the city can vary greatly in the amount of crime they experience. The community area with the most amount of crime is Austin with 61,169 crimes in our dataset, and the area with the least was Edison Park with 1,284. We would have preferred to use crime rate (per capita) but I was not able to find reliable and recent data for population by community area. 

## Correlation Discussion

There seems to be a moderate linear positive relationship between the average monthly temperature and the monthly total count of crimes. The r value and the scatter plot both indicate this. This seems to make sense as it gets warmer, I would think people are more likely to be out and drinking. The summer months are warmer but also high school and college students would be out of school so that may contribute as well.

## Hypothesis testing for correlation - T-test

$H_{o}$: There is not a linear relationship between average monthly temperature and monthly crime total. 

$H_{a}$: There is a linear relationship between average monthly temperature and monthly crime total. 

p-val = .0000385

Since our p-value is less than 0.05, we can reject the null hypothesis. There is sufficient evidence that there is a linear relationship between the average monthly temperature and monthly crime total.