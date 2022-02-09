# Bike Sharing Assignment
Consider a bike-sharing company that offers a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. They are planing to accelerate their revenue as soon as the ongoing lockdown comes to an end. They want to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation. For this, they have gathered a large dataset on daily bike demands across the American market based on some factors. Essentially, the company wants to know —
* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Background**: A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. 

- **Aim**: Which variables are significant in predicting the demand for shared bikes.

- **Data**: Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Based on the performance (R2 = 0.801) and using variable selection, 
- I have chosen model_6 as the final model.
- I have reduced the number of variables from 30 to 16 (almost ~50% reduction).
- If we don't consider the dummy variables then we have only 9 unique variables in the final model.
- 'temp', 'day_diff' and 'weathersit_3' are the top three features having most influence on the bike demand.
- 'temp' is positively correlated with the bike demand, suggesting bike demand is higher during summer.
- 'day_diff' shows that bike demand has an increasing trend with the time so company should increase the number of bikes every year.
- 'weathersit_3' has a negative coefficient indicating a decrease in bike demand during
- rainy and snowy weather, its because people tend to avoid travelling in rainy and snowy conditions.
- Humidity is high during rainy season and is  has negative coefficient supporting the previous observation.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy - version 1.19.5
- Pandas - version 1.1.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.2
- statsmodels - version 0.10.2
- sklearn - version 1.0.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@siddharth-ghule-work-gmail] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
