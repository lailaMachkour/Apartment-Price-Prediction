# Apartment-Price-Prediction

Overview

This project involves scraping apartment data from Avito (a popular online marketplace), performing data cleaning, and building a prediction model to estimate apartment prices. The project is divided into three main parts:
Web Scraping: Extract apartment data from Avito using a custom scraping script.
Data Cleaning: Prepare the raw dataset by handling missing values, formatting data, and feature engineering.
Prediction Model: Apply machine learning techniques to predict apartment prices based on the cleaned dataset.

Files

prediction.ipynb: This notebook contains the data cleaning process and the prediction model. It includes all steps from loading the dataset to applying a machine learning algorithm to predict apartment prices.
Appartements.csv: The dataset used for training the prediction model. This file includes raw data scraped from Avito, consisting of features like apartment location, size, price, and other relevant attributes.
web Scraping avito.ipynb: The notebook responsible for scraping data from Avito. It automates the collection of apartment listings with features such as price, location, and other relevant parameters.

Project Steps

1. Web Scraping

The web Scraping avito tp1.ipynb file contains the code to scrape apartment listings from Avito. The data collected includes:

Apartment price
Location (city, district)
Size (square meters)
Number of rooms
Additional features (e.g., parking, elevator)
The scraping is done using BeautifulSoup and Selenium to navigate through the Avito website and extract the necessary information.

2. Data Cleaning

The data cleaning process, detailed in the prediction.ipynb notebook, involves:

Handling missing values
Normalizing and encoding categorical variables (e.g., location)
Removing outliers to improve model accuracy
Feature engineering: creating new relevant features for the prediction model

3. Prediction Model

In prediction.ipynb, after cleaning the data, a machine learning model is trained to predict apartment prices. The model uses features such as apartment size, location, and number of rooms. 

Steps include:

Splitting the dataset into training and testing sets
Applying a regression algorithm to predict prices
Evaluating the model's performance using metrics such as Mean Squared Error (MSE)
