# Logistic-optimization

# Gokada Delivery Drivers Location Optimization

## Table of Contents
- [Project overview](#introduction)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This repository contains code and data for optimizing the placement of delivery drivers on a last-mile delivery service in Nigeria. The goal is to reduce unfulfilled delivery requests by analyzing historical data and identifying key factors influencing order completion.

## Data Exploration

### Steps:

1. **Data Loading**: Load the provided datasets (`completed_orders.csv(nb.csv)` and `delivery_requests.csv(driver_locations_during_request.csv)`).
2. **Missing Values and Outliers**: Check for missing values and outliers in the datasets and handle them appropriately.
3. **Exploratory Data Analysis (EDA)**: Explore the distributions of key variables, identify patterns, and correlations between variables.
4. **Feature Extraction**: Extract relevant features based on time and location, such as rain vs no-rain, holidays, traffic conditions, etc.
5. **Feature Scaling**: Normalize or scale features where necessary.
6. **Distance and Key Variables**: Write a program to compute distances, driving speed, shortest distance, driving route distance, etc., between geographic coordinates and timestamps.
7. **Riders and Orders in Circles**: Compute the number of riders and orders within circles of 500m around accepted and unfulfilled orders.
8. **Clusters of Delivery Locations**: Identify clusters of delivery starting locations and destinations using clustering algorithms.
9. **Visualization**: Create purpose-driven visualizations using Python libraries like Matplotlib, Seaborn, or Datashader.

## Installation

1. Clone the repository:

    git clone git@github.com:Betfsh/Logistic-optimization.git
    cd Logistic-optimization

2. Create a virtual environment using Python 3.10:
    ```bash
    python3.10 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ``

## Contributors
Bethelhem Mebratu

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
MIT