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

#### Goal of this analysis:

The goal of this analysis is to measure the effectivity of the Automated Speed Enformcement (ASE) program is in Chicago. Under ASE program, speed cameras has been installed in the childern safety zones of chicago. These cameras capture speed violations in these areas. It is important to have this program in these areas as a part of safety for children by slowing donw the speed of vehicles in these areas and avoiding the crashes. 


Our main aim is to reduce the number of crashes in the children safety zones of Chicago and the main questions to be anwered with this analysis are :
- (1) Is there any impact of this program on the number of speed violations in the speed camera enforced areas?
- (2) Is there any impact of this program on the number of crashes in the speed camera enforced areas?
- (3) Is there any impact of speed violations on red light violations which is one of the major causes of crashes?
- (4) Are the drivers aware of this program?


#### Derivation of Insights from the final datasets


##### Insight 1: Does decreasing speed violation also reduces the number of accidents in that area?

###### Analysis: 
The idea here is to analyze impact of speed camera violations on number of crashes. Since, speed is one of the major causes of the crashes, it is important to see how these two are related in speed camera enforced areas. It has been observed that over the period of time, the number of speed violations are decreasing under the Automated Speed Enformcement (ASE) program in chicago. 

Trend of speed violations under ASE in chicago  |  Trend of speed violations and crashes in speed camera enforced areas
- | -
![IP_FV_overall_trend_speed_violations.PNG](https://github.com/VikitaNayak/Individual-Project-First-Version/blob/master/IP_Viz1.PNG) | ![RV_IP_Insight1.PNG](RV_IP_Insight1.PNG)
- | -
Graph 1 | Graph 2


