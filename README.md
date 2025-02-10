## Phase-1-project
## Aviation Accident Database & Synopses, 1996 to 2023
### Author: Maryan Daud

## Overview
![Air Craft](Images\aircraft-155380716-612x612.jpg)

This project aims to analyze aviation accidents dataset to identify the types of aircrafts that are more prone to accidents and determine safest and lowrisk aricrfats for purchase.We will also determine the type of accidents occuring on certain aircrafts and identify crash trends, patterns and relationships with weather, locations and other variables. We will use exploratory data analysis to generate insights for Dragon Airline.

## Business Problem
Dragon Airline company is expanding into new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. We will determining which aircraft are the lowest risk for the company to start this new business endeavor and translate our findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

### The key business questions are;

What is the safest aircraft for Purchase?

Which external factors(weather/location)contribute to highest number of accidents/incidents? 

Trends of crashes overtime?

Relationship between Fatalities/Injuries versus Aircraft qualities?

## Data
The NTSB aviation accident database contains information from 1946 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters

#### Source: National Transportation Safety Board (NTSB)

In the folder are Aviation datasets from:

1. [Aviation Data Set](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)

The data set has two files sets.The files are,in compressed CSV (comma-separated values) formats files and contains information on the US State name and the abbreviation of them and The NTSB aviation accident database contains information from 1946 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters. The aviation data is organized into several tables and 31 columns containing different information about the Aviation accidents e.g investgation type,date of event,location, .Some of the challenges encountered during data preparation included missing values,duplicates and spliting date sets.

## Methods
This project uses exploratory data analysis to generate insights for a saftey of flights and safest airlines and routes.

## Results 

In determining the safety of aircrafts data  the aircraft make with most accidents is the Cessna and piper while the Mulholland Robert A reported the least number of accidents.

![Aircraft Make](Images\image-2.png)

The data shows various external factors contribute to higher occurence of accidents/incidents such as location,with Anchorage AK attributing to majority of the incidents/Accidents 

![Location](Images\image-6.png)

Almost all Accidnets/Incidents occur during VMC weather condition weather 

![Weather Condition](Images\image-5.png)

With Majority of incidents/Accidents happening during takeoff and landing according to broadphase of flights 

![Broad Phase on Flight](Images\image-4.png)

No meaningful correlation between fatality/Injuries over the years meaning total injuries or fatality haven't changed significantly over time.

A weak positive correlation between Fatal Injuries and Injuries vs Number of Engines showing that aircraft with more engines show slightly higher fatal injuries.

This further analysis shows that although more accidents are recorded in aircrafts with less engines that is less than 3 the chances of injury and death is less likely as compared to aircrafts with more engines 

![Correlation](Images\image-3.png)


## Conclusion 

In conclusion this avaiation dataset has provided a comprehensive view on aircraft accident trends overtime , provided best routes and weather conditions for flying and provided insights on areas to optimize flight safety, we therefore conclude that 

1. Better quality aircrafts and saftey protocols over the years with a notable decline of aircraft accidents/incidents over the years

2. There are fewer accidents recorded with multiple engine aircrafts greater than 3 and the Mulholland Robert A and Detrick Donald G make

3. There is need to consider landing and takefoff as the riskiest time during the broadphase of flight 

4. External factors such as weather and location/routes contribute to a higher risk of accident/incident occurence 

5. Company should venture into business work use and private/corporate use as there is likely accidents as compared to other uses such as personal and instructional use

## Reccomendation 

We reccomend:

1. Improved safety measures and better aircraft quality production over the years adopting better perfoming makes/models crafts and engines 

2. Procure aircrafts with more engines greater than three and from makes with less than 5 recorded accidents over the years such as Mulholland Robert A and Detrick Donald G 

3. There is need to develop inhand SOPs/Guides/Protocols to guide pilots and flight crew in different stages of flight broadphase especially during takeoff and landing  

4. Limit flying of aircraft during VMC weather condition during flight planning and operations 

4. Assessment/Investigation with preliminary findings of airport routes and flight towers in Anchorage, Miami , and Albuquerque NM  and further data exploration.Company should set up flight routes in other airports as they await findings.

### For more information 

See full analysis in the: (aviation.ipynb)





[def]: C:\Users\User\Desktop\MORINGA\Phase_1\dsc-phase-1-project-daud\Images\aircraft-155380716-612x612.jpg