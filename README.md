# Project Title: Predicting Demand for Shared Bikes
>  ## Overview
This project aims to build a multiple linear regression model to predict the demand for shared bikes based on various factors. The prediction model will help BoomBikes, a US-based bike-sharing provider, understand the factors influencing bike demand and prepare a strategic plan to meet customer needs post-COVID-19.


## Table of Contents
* [General Info](#general-information)
* [Project Structure](#Project-Structure)
* [Setup and Requirements](#Setup-and-Requirements)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- <b>Background</b>: The rising popularity of shared bikes as a sustainable and convenient mode of transportation requires effective demand forecasting to optimize bike availability.
- <b>Business Problem</b>: The key challenge is to accurately predict the number of bike rentals, which helps in efficient resource allocation and better customer service.
- <b>Dataset</b>: The dataset includes features such as weather conditions, temperature, humidity, wind speed, time of the day, and holiday status. This data is utilized to forecast the bike rental demand.


## Project Structure
- `day.csv`: The dataset used for building the prediction model.
- `bike_sharing_demand_prediction.ipynb`: Jupyter notebook containing the code for data preprocessing, model building, and evaluation.
- `README.md`: This README file.

## Setup and Requirements
Ensure you have the following Python packages installed:

- pandas
- numpy
- scikit-learn
- statsmodels
  
You can install the required packages using pip:
`pip install pandas numpy scikit-learn statsmodels`
## Technologies Used
- python - version 3.11.9
  - Pandas - version 1.3.3
  - NumPy - version 1.21.2
  - Scikit-learn - version 0.24.2
  - statsmodels - version 0.14.2

## Conclusions
- Key Factors Influencing Demand: Weather conditions, particularly temperature and humidity, significantly affect bike rental rates.
Peak Demand Times: Demand peaks during certain hours of the day, highlighting the importance of time in predicting rentals.
- Holiday Effect: There is a noticeable difference in demand on holidays compared to regular days, indicating that holiday status is a crucial feature.
- Model Performance: The multiple linear regression model provides a good fit, explaining a significant portion of the variance in bike demand.



## Acknowledgements
- This project was inspired by real-world business case from United States.


## Contact
Created by [@ManisCodeBase] - feel free to contact me @ manifordev@gmail.com!
