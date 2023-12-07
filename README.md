# Project4 : West Nile Virus Prediction

# Problem Statement

“In 2011 and 2013, in order to prevent West Nile Virus; WNV Infection in Chicago, insecticide sprayings are conducted in some specific areas to reduce the number of mosquitoes. 

Anyways, after gaining the number of mosquitoes caught in traps around Chicago city  on the spraying days, Government of Illinois are suspected if the Chicago City Council  were doing the right way as the number of mosquitoes and the number of West Nile Virus sampling cases  still increased even after spraying dates.

Head of Data Science of Government of Illinois found that the spraying location were not matched with the major outbreaking areas so they were  curious on how they determined the spraying locations. 

After meeting with Chicago City Council, Government of Illinois requested the Head of Data Science and his team to develop a classification model that can notify the risk of West Nile Virus outbreaks in specific geographic regions in Chicago.

In the Data Science team splint planning, the team decided to use daily local weather data to create the classification model after studying the West Nile Virus.”


# Data dictionary

|Feature|Type|Description|Dataset|
|---|---|---|---|
species|string|Species of the trapped mosquitoes|train|
trap|string|Mosquitoes Trap ID|train|
month|int|Recording month|train|
year|int|Recording year|train|
Tmin|int|Minimum temperature of the date|weather|
Dewpoint|int|Daily average Dewpoint|weather|
WetBulb|int|Daily average Wet Bulb|weather|
Heat|int|Daily average Wet Bulb|weather|


# Summary and Recomendation

After creating 6 models, the data science team decided to deliver Logistic Regression with GridSearchCV Model, as a first proposal to Government of Illinois, which is able to detect 68% of  total West Nile Virus presence on unseen dataset. In addition,  from the predicted results of the model,  only 15% of the predicted presence of West Nile Virus is actually existed, which might lead to over-budgeting on hospitality expense in Chicago. If Government of Illinois approved to use this model, Chicago City Council also needs to find countermeasures for operation cost-saving.
As for spray that not effective might change to use Aerial spraying that is process by Airplanes and helicopters to treat very large areas with larvicides that kills mosquito larvae that hatch from eggs or adulticides to quickly kills flying mosquitoes.Both larvicides and adulticides can temporarily help reduce the number of mosquitoes in an area.


# Cost - Benefit Statement
Early intervention can help prevent the spread of the virus, reducing the overall cost of responding to a widespread outbreak and lowers the burden on healthcare systems.This can lead to sustained cost savings in public health expenditures related to WNV surveillance, treatment, and response in the future.
