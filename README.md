# Solving the Water Crisis in Tanzania -- Exploring Water Well Functionality


### Project Overview
Today Tanzania is facing an important water crisis with millions amongst its population currently lacking access to safe, clean water and sanitation. As a result, many people are suffering. 
In this project, the objective is to dive into this crisis, focusing on the analysis of water well functionality accross the country in order to assess the level of the crisis and explore some possible solutions towards improving the situation for millions of people. 

![alt text](https://github.com/anaulianova/Data-Mining-Water-Pumps-in-Tanzania/blob/main/Images/Image.PNG)

### Data
>	Data on Water Pumps in Tanzania, (Source: Driven Data); 

### Methodology

- Clean data and perform EDA on the various features included
- Prepare the data for modeling
- Examine the performancec of a baseline KNN and RandomForest model


##### Findings & Recommendations

###### Almost half of Tanzania's water pumps recorded in the data are either non-functional or need repair

![alt text](https://github.com/anaulianova/Data-Mining-Water-Pumps-in-Tanzania/blob/main/Images/Well%20Fucntionality.png)

Although Tanzania has naturally abundant water resources, its population's water crisis is compounded by the large number of on-functional wells spread throughout the country. As a result, people, especially women and children, are forced to travel even further distances in order to secure a bucket of water, with no guaranteee that it will be clean or good qualty water. This is especially true in rural areas, who still primarily depend on water from communal boreholes, as is evident in the data. 

Indeed, we can see below the concentration of water pumps in selected regions in the country:

![alt text](https://github.com/anaulianova/Data-Mining-Water-Pumps-in-Tanzania/blob/main/Images/Functionality%20Map%20(1).png)
![alt text](https://github.com/anaulianova/Data-Mining-Water-Pumps-in-Tanzania/blob/main/Images/Functionality%20Map%20(2).png)


> Recommendations:

- The Tanzania Water Ministry should focus its funding allocated to addressing the water crisis towards the development of better water distribution networks, particularly in rural areas, relying on local authorities managing water supplies.
- FOr the development of new water pumps, location is factor in ensuring the wlongevity of the water well's functionality. Thus these developments should be focused on areas with abundant groundwater resources of good quality, that would then be distriuted through efficient distribution networks. 
- In addition, the government should also further liaise with local authorities in a select number of districts to ensure the management is fully regulated in order to reduce the amount of wtaer wells operating without permits which appear to be concentration in a select number of regions in the country.


### Future Work
Provided more time, future work would look more closely at the important features identified through the models explored in order to narrow down recommednations towards specific action points. 
These features would be examine alongs the following axis:
- Natural Resource: looking closer at the specificities of the qulality, quantity and other such features to assess their impact on well functionality to provide more specific ecommendations on better locations for water pump development
- Management: looking at the combination of features that could inform 'best practices' for the management and operation of water wells in the country to ensure the longevity of their functionality

