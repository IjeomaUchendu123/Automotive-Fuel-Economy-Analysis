# Automotive-Fuel-Economy-Analysis

## TABLE OF CONTENTS

 - [PROJECT OVERVIEW](#project-overview)
 - [DATA SOURCES](#data-sources)
 - [TOOLS](#tools)
 - [DATA CLEANING](#data-cleaning)
 - [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
 - [DATA ANALYSIS](#data-analysis)
 - [FINDINGS](#findings)
 - [RECOMMENDATIONS](#recommendations)
 - [LIMITATIONS](#limitations)

## PROJECT OVERVIEW

An Automotive fuel economy analysis gaining insights into relationships between cars and their mpg's, horsepower, weight, car cylinders and origin.

<img src="https://github.com/user-attachments/assets/5dcacd14-bebf-4bce-bf7c-036df8c59af1" alt="Fuel Economy Visualization">


### DATA SOURCES

The Primary dataset used for this analysis is the "Fuel_Economy_Dataset.csv" file gotten from online data sources, containing detailed information about each vehicle.

### TOOLS
- Excel - Data Cleaning and Visualization [Download_here](https://microsoft.com)

### DATA CLEANING

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
### FINDINGS

The Findings from the analysis are summarised as follows;
1. The top car rating by horsepower is the Buick Electra 225 Custom.
2. The relationship between the weight of the cars and the Mpg is a positive relationship. The higher the weight of the cars, the higher the Mpg.
3. Cars with 4 cylinders has the highest distribution while cars with 5 cylinders has the least.
4. The most number of cars were produced in model year 73.
5. 63% of the cars are of origin 1 which is the highest .
6. The bottom 3 cars by Mpg are chevy c20, ford f250, hi1200d.

### RECOMMENDATIONS
Based on the analysis, the following actions are recommended;
1. Focus on the production of cars with 4 cylinders to cater to market demand.
2. Improve fuel efficiency in cars with more weight.
3. Increase production in model years with high demand such as model year 73.
4. Target regions with high demand for origin 1 cars since it has 63% of the market shares.
5. Encourage consumers to opt for lighter cars so as to improve their fuel efficiency.


### LIMITATIONS

They were missing values which i had to treat using the k-n-n approach. They were also a few outliers on the Horsepower field which was discovered when i checked using the quartile range.
