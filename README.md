# Automotive-Fuel-Economy-Analysis

## PROJECT OVERVIEW

An Automotive fuel economy analysis gaining insights into relationships between cars and their mpg's, horsepower, weight, car cylinders and origin.

### DATA SOURCES

The Primary dataset used for this analysis is the "Fuel_Economy_Dataset.csv" file gotten from online data sources, containing detailed information about each vehicle.

### TOOLS
- Excel - Data Cleaning and Visualization [Download_here](https://microsoft.com)

### DATA CLEANING/PREPARATION

In the data preparation phase we performed the folowing task
1. Data Inspection
2. Idenfiying outliers

### EXPLORATORY DATA ANALYSIS
This involved exploring the data to answer key questions such as;

 - What are the top 5 cars by horsepower
 - What is the relationship between car weight and Mpg
 - What is the distribution of cylinders for the cars
 - What are the number of cars produced for each model year
 - What origin has the highest number of cars produced
 - What are the bottom 3 cars by Mpg

### DATA ANALYSIS

```Excel
=IF(OR([@horsepower2]<$N$7,[@horsepower2]>$N$6),TRUE,FALSE)
QUARTILE(E2:E399,1)
QUARTILE(E2:E399,3)
```
### RESULTS/FINDINGS

The Findings from the analysis are summarised as follows;
1. The top car rating by horsepower is the Buick Electra 225 Custom.
2. The relationship between the weight of the cars and the Mpg is a positive relationship. The higher the weight of the cars, the higher the Mpg.
3. Cylinder 6 has the highest distribution with Cylinder 36 being the least.
4. The most number of cars were produced in model year 73.
5. Origin number 1 has the highest number of cars produced.
6. The bottom 3 cars by Mpg are chevy c20, ford f250, hi1200d.

### RECOMMENDATIONS
Based on the analysis, the following actions are recommended 


### LIMITATIONS

They were missing values which i had to treat using the k-n-n approach. They were also a few outliers on the Horsepower field which was discovered when i checked using the quartile range.
