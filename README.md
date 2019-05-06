# Individual-Project-Revised-Version
###### Submitted By Vikita Nayak

#### Background: 

This document is the revised version of the individual Project [Exploratory Data Analysis](https://github.com/VikitaNayak/Individual-Project/blob/master/README.md) and [First Version.](https://github.com/VikitaNayak/Individual-Project-First-Version/blob/master/README.md)
- The Individual Project Exploratory Data Analysis included 5 distinct visualizations which were created from the Speed Camera Violation dataset. 
- The Individual Project first version included finding 3 key insights from the data analysis of 4 different datasets including Speed Camera Violation dataset

#### Goal of this project: 
- The final version of your data product.
- A documentation of your data product.
- The final version should make use of advanced and interactive features of Tableau

#### About the Datasets

In total, 4 datasets have been used for this analysis and below are those:
-  Dataset 1 : Speed Camera Violation
-  Dataset 2 : Traffic Crashes - Crashes
-  Dataset 3 : Red light Violation
-  Dataset 4 : Ward Dataset

##### Final Dataset creation:

- Data cleaning in python and excel to remove the null values and extra columns
- Extracted zipcodes from location in traffic crashes datasets using google API in python. [Code for reference.](https://github.com/VikitaNayak/Individual-Project-First-Version/blob/master/%5BIndividual%20Project%5D%20Python%20code%20to%20generate%20zipcodes%20from%20location.ipynb)
- Extracted zipcodes from Ward Dataset and Vlookuped in the Speed Camera Violation Dataset
- Extracted zipcodes from Ward Dataset and Vlookuped in the Red Light Camera Violation Dataset
- Removed extra columns not required for analysis from all three tables
- Merged(joined) the above 3 datasets in Tableau based on zipcodes


###### Dataset Reference

- Ward Dataset Reference : https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Ward-Offices/htai-wnw4

- Data set 1 Reference :https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4)

- Data set 2 Reference : https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if)

- Data set 3 Reference : https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37
