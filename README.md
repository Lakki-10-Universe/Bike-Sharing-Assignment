# Bike Sharing Assignment
## Objective:
BoomBikes aspires to understand the **demand for shared bikes among the people** after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this **to prepare themselves to cater to the people's needs** once the situation gets better all around and **stand out from other service providers and make huge profits**.

    
> For this purpose, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
> - **Which variables are significant in predicting the demand for shared bikes.**
> - **How well those variables describe the bike demands**

## Goal:
**Build a Multiple Linear Regression Model for the Prediction of Demand for Shared Bikes**

Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

**The model should be built taking the 'cnt' column in the dataset as the Target Variable**.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
1. What is the background of your project?
    > This project is part of the IIITB PGDM program in ML & AI, focusing on skills in Exploratory Data Analysis (EDA) and building a Linear Regression model.
2. What is the business probem that your project is trying to solve?
    >The goal is to identify and quantify key factors influencing shared bike demand in the US market. This predictive analysis will help guide strategies for optimizing bike availability, pricing, feature building and possible market expansion.
3. What is the dataset that is being used?
    > The dataset, day.csv - provides daily cumulative rental data spanning two years, capturing patterns in bike demand and other relevant variables.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### The final model predicts the Demand through this equation:
$$ Final Model Equation = const \times 0.1724 + yr \times 0.2401 + holiday \times -0.0985 + temp \times 0.4623 + LightSnowRain \times -0.2857 + MistCloudy \times -0.0754 + spring \times -0.1258 + winter \times 0.0587 $$
Looking at the final model equation, the top 3 features with the highest absolute values of coefficients (positive or negative) are:
1. **Temperature** (temp) with a coefficient of 0.4623: This shows temperature has the biggest impact on bike demand. When it’s warmer, demand goes up, which makes sense since people find it easier to bike in nice weather.
2. **LightSnowRain** with a coefficient of -0.2857: This has a strong negative impact, meaning that
when there’s light snow or rain, bike demand drops a lot because of bad weather.
3. **Year** (yr) with a coefficient of 0.2401: This positive coefficient means that demand is rising over time, suggesting that bike-sharing has become more popular each year.


**So, temperature, weather (light snow/rain), and year are the main factors affecting bike demand in this model**


## Technologies Used
    - Python - Version 3.17
    - Pandas - Version 2.1.4
    - NumPy - Version 1.26.4
    - Matplotlib - Version 3.8.0
    - Seaborn - Version 0.13.2
    - Jupyter Notebook - Version 7.0.8

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Data Source: The day.csv dataset provided for this analysis from UpGrad.
- Educational Resources: Various online resources and courses that helped in learning EDA, Linear Regression.


## Contact
Created by [@Lakki-10-Universe] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->