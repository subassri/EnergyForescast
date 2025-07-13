# PowerPulse: Household Energy Usage Forecast
## Overview
This repository contains code for predicting household energy consumption using machine learning models. The code loads a dataset, performs exploratory data analysis, preprocesses the data, trains multiple models, and evaluates their performance.

## Features
* Data loading and preprocessing
* Exploratory data analysis (EDA) before and after preprocessing
* Training of multiple machine learning models (Linear Regression, Random Forest, Gradient Boosting, Neural Network)
* Model evaluation using RMSE, MAE, and R² metrics
* Visualization of actual vs predicted values for each model

## Requirements
* Python 3.x
* pandas
* numpy
* plotly
* scikit-learn
* scipy

## Usage
1. Clone the repository: `git clone https://github.com/subassri/EnergyForescast.git`
2. Install required libraries: `pip install -r requirements.txt` (if available) or install individually
3. Run the code: `python Energypower.ipynb` 

## Dataset
The dataset used is the Household Power Consumption dataset, which can be downloaded from https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption 

## Models
The following models are trained and evaluated:

* Linear Regression
* Random Forest
* Gradient Boosting
* Neural Network

## Performance Metrics
The models are evaluated using the following metrics:

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R² (Coefficient of Determination)

## Results
The best-performing model is selected based on the R² metric. The actual vs predicted values for each model are visualized using scatter plots.
