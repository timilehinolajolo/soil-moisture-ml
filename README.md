# Predicting Soil Moisture Dynamics Using Environmental Variables

## Overview
This project explores whether environmental variables such as temperature, relative humidity, rainfall, and sampling depth can be used to predict soil moisture in an agricultural field at the Federal University of Agriculture, Abeokuta (FUNAAB).

Soil moisture is important for irrigation and soil-water management. Although the gravimetric method provides a reliable way to measure soil moisture, collecting measurements repeatedly can be time-consuming. This project looks at whether machine learning can help estimate soil moisture from environmental measurements that are easier to collect.

## Research Questions
1. How accurately can temperature, relative humidity, rainfall, and sampling depth predict soil moisture under FUNAAB field conditions?
2. How does Random Forest compare with Linear Regression for this prediction task?
3. Which variables have the greatest influence on the predictions?

## Methodology
* **Current stage:** Building and testing the machine learning pipeline using synthetic data.
* **Next stage:** Collecting field data at FUNAAB over a 30-day period and measuring soil moisture using the gravimetric method.
* **Models:** Linear Regression and Random Forest Regression.

## Project Structure
* `notebooks/01_data_exploration.ipynb` — Exploratory data analysis and visualisation.
* `notebooks/02_preprocessing.ipynb` — Data cleaning, missing values, and feature preparation.
* `notebooks/03_modeling.ipynb` — Model training, evaluation, and comparison.

## Project Status
This is an ongoing undergraduate research project. The current implementation is a prototype, with field data collection planned as the next major stage.