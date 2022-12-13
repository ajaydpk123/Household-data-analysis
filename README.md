# Household-data-analysis
EDA on Household data using python and its libraries.

## Dataset
Data consists of 20640 rows and 10 features:

longitude: A measure of how far west a house is; a higher value is farther west

latitude: A measure of how far north a house is; a higher value is farther north

housingMedianAge: Median age of a house within a block; a lower number is a newer building totalRooms: Total number of rooms within a block

totalBedrooms: Total number of bedrooms within a block

population: Total number of people residing within a block

households: Total number of households, a group of people residing within a home unit, for a block

medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)

medianHouseValue: Median house value for households within a block (measured in US Dollars)

oceanProximity: Location of the

## code files
[Household data analysis.ipynb](https://github.com/ajaydpk123/Household-data-analysis/tree/master/CODE)

## Exploratory Data Analysis
Performed EDA and tried answering the following questions:
1. What is the average median income of the data set and check the distribution of data using appropriate plots. Please explain the distribution of the plot.
2. Draw an appropriate plot to see the distribution of housing_median_age and explain your observations.
3. Show with the help of visualization, how median_income and median_house_values are related?
4. Create a data set by deleting the corresponding examples from the data set for which total_bedrooms are not available.
5. Create a data set by filling the missing data with the mean value of the total_bedrooms in the original data set.
6. Write a programming construct (create a user defined function) to calculate the median value of the data set wherever required.
7. Plot latitude versus longitude and explain your observations.
8. Create a data set for which the ocean_proximity is ‘Near ocean’.
9. Find the mean and median of the median income for the data set created in question 8.
10. Please create a new column named total_bedroom_size. If the total bedrooms is 10 or less, it should be quoted as small. If the total bedrooms is 11 or more but less than 1000, it should be medium, otherwise it should be considered large.
