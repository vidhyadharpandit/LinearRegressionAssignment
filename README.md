# Linear Regression Assignment
> This assignment is a programming assignment wherein attendee have to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
- The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.
- They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- Objective is to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
-   Which variables are significant in predicting the demand for shared bikes.
-   How well those variables describe the bike demands
-   Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model was developed using Recursive Feature Elemination (RFE) approach. All variable were added together to the model and depending on p-value and VIF specific columns were removed and model was recreated.
- Model gave the R-squared score fo 84% on the training data and 81% testing data

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Libraries and packages used were numpy, pandas, matplotlib.pyplot, seaborn, sklearn, sklearn.model_selection, sklearn.preprocessing, statsmodels.api, statsmodels.stats.outliers_influence, sklearn.metrics

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Upgrad and IIIT teams for learning and guiding thorugh recorded sessions, texts and live sessions.

## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
