# Car Purchase Prediction Using Decision Tree

This project aims to predict whether a person is eligible to purchase a car based on their age, gender, and annual salary. The prediction model is built using the Decision Tree algorithm and deployed via a web interface using Heroku.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Goals](#goals)
4. [Project Steps](#project-steps)
5. [Web Application](#web-application)
6. [Deployment](#deployment)
7. [Authors](#authors)
8. [License](#license)

## Project Overview

This project analyzes a dataset consisting of user demographics and their purchasing decisions to create a predictive model. The project utilizes a Decision Tree classification model and aims to predict whether a customer will purchase a car or not, based on specific attributes such as age, gender, and annual salary.

The results are presented through a web application that allows users to input their data and receive feedback on their eligibility to purchase a car.

## Dataset

The dataset used in this project contains 1000 rows and 5 columns, which are:

1. **User ID** - A unique identifier for each user.
2. **Gender** - The gender of the user.
3. **Age** - The age of the user.
4. **Annual Salary** - The annual salary of the user.
5. **Purchase Decision** - The target label indicating if the user purchased a car (Yes = 1, No = 0).

### Dataset Preprocessing

- Labels were transformed from categorical to numerical values to fit the Decision Tree model.
  
## Goals

The primary goal of the project is to build a model that can accurately predict whether a person should be considered eligible to purchase a car, based on their age, gender, and annual salary.

## Project Steps

1. **Data Preprocessing**:
   - Categorical labels (e.g., Gender) were converted to numerical values.
   
2. **Modeling**:
   - The data was split into a training and testing set (80% training, 20% testing).
   - The Decision Tree algorithm was used to create the prediction model.
   - The model was saved using `joblib` for future use.

3. **Web Application**:
   - A simple web interface was created using a car application template.
   - The dashboard displays whether a user is eligible to purchase a car based on the inputs provided.

4. **Styling & Deployment**:
   - The web application was styled using HTML and CSS.
   - The project was deployed using Heroku.

## Web Application

You can interact with the prediction model using the web application deployed at:

- [Car Purchase Decision Prediction Application](https://car-purchase-decision-b3e32651a9e4.herokuapp.com)

## Deployment

The project was deployed on Heroku for easy access and usage. The application is live at:

- [Heroku Application Link](https://car-purchase-decision-b3e32651a9e4.herokuapp.com)

## Authors

This project was developed by:

- Shabrina Aurelia (5201811001)
- Aziz Prabowo (5201811004)
- Nuzula Afini (5201811006)
- Frisca Damayanti (5201811009)
- Neni (5201811010)
- Maharani Yulianti (5201811012)
- Febrina Helmaputri (5201811014)
- Meylany Putri Maharani (5201811016)

## License

--
