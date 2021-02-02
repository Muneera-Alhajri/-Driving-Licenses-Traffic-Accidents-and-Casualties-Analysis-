# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Driving Licenses, Traffic Accidents and Casualties Analysis

### Authors
Muneera Alhajri
### Date
3rd jan 2021


## Overview
First project in Data Science Immersive course with General Assembly.


## Executive Summary
In this project we worked on two data sets: driving licenses, and traffic accidents, and we find some associations that we build our recommendations to find solutions. We find that there is a huge difference between the three largest regions and the other regions in Saudi Arabia, these regions are Makkah, Riyadh, and Eastern. We also find that the number of accidents is decreasing through the years while the number of licenses is increasing, Which is an excellent predictor.



## Datasets

### Provided Data

For this project, I used two provided datasets:

- [Traffic Accidents and Casualties by Region](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-traffic-accidents-2008.csv)
- [Driving Licenses Issued By Administrative Area](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-driving-licenses-2004-2008.csv)

### Data Dictionary

#### Traffic Accidents
|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Traffic_Accidents|Year in which the accident occured| 
|region|object|Traffic_Accidents|Region in which the accident occured| 
|indicator|object|Traffic_Accidents|Measurement about the demages (No. of accidents - No. of dead)|
|Value|int|Traffic_Accidents|value of the indicator|
|geo_point_2d|object|Traffic_Accidents|Location of the accident occured|
|x|float|Traffic_Accidents|longitude of center the city| 
|y|float|Traffic_Accidents|Latitude of center the city| 

#### Driving Licenses
|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Driving_Licenses|Year in which the accident occured| 
|region|object|Driving_Licenses|Region in which the accident occured| 
|driving_licenses|int|Driving_Licenses|Number of issued licenses per year|
|geo_point_2d|object|Driving_Licenses|Location of the accident occured|
|x|float|Driving_Licenses|longitude of center the city| 
|y|float|Driving_Licenses|Latitude of center the city| 

## Blog post

https://muneera-alhajri1997.medium.com/driving-licenses-traffic-accidents-and-casualties-analysis-in-2019-3ee5f7f8df72

## Conclusions and Recommendations

I think with more informative features, we can come up with a more informative analysis such as the cause of accidents, price of fuel (because there was a significant change after implementing VAT and increasing fuel prices [1]), more year data for accidents to look at how ‘Saher’ affects the number of accidents.
We can conclude that some of the regions have a large population so the number of licenses may not be affected by the new law. We need to have strict laws, and processes that simplify the way to apply this law. In order to prevent any loss, social awareness campaigns are necessary to remind people that they must follow the rules and respect the road and other drivers.


## Acknowledgments
I would like to express my special thanks of gratitude to my teachers Husain Amer,Amjad Alsulami, Amal Alzamel, and Mukesh Mithrakumar who gave me the golden opportunity to do this wonderful project on the topic (Driving Licenses, Traffic Accidents and Casualties Analysis), which also helped me in doing a lot of Research and i came to know about so many new things I am really thankful to them.
Secondly i would also like to thank my friends who helped me a lot in finalizing this project within the limited time frame.




