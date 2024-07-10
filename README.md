# Building Energy Benchmarking and CO2 Emissions Analysis

## Project Overview

This project analyzes CO2 emissions and energy consumption data for buildings in Seattle, using data collected in 2016. The goals are to provide an analysis of the current state of emissions and energy consumption, identify factors impacting CO2 emissions, and develop a predictive model for future emissions and energy consumption for buildings without existing measurements. A dashboard will be created for visualization and model interpretation.

## Table of Contents

- [Data](#data)
- [Modeling](#modeling)
- [Results](#results)
- [Dashboard](#dashboard)
- [License](#license)

## Data

The dataset used for this project is the Building Energy Benchmarking dataset provided by the City of Seattle. It includes information on energy consumption, CO2 emissions, and various building characteristics for the year 2016.


### Data Description

- `OSEBuildingID`: Unique identifier for each property.
- `DataYear`: The year of the data collection.
- `BuildingType`: Classification of the building type.
- `PrimaryPropertyType`: Primary use of the property.
- `PropertyName`: Official or common name of the property.
- `Address`: Address of the property.
- `City`: City of the property.
- `State`: State of the property.
- `ZipCode`: Zip code of the property.
- `Latitude`: Latitude coordinate.
- `Longitude`: Longitude coordinate.
- `YearBuilt`: Year the property was built.
- `NumberofBuildings`: Number of buildings in the property.
- `NumberofFloors`: Number of floors in the property.
- `PropertyGFATotal`: Total floor area of the property.
- `PropertyGFAParking`: Parking area of the property.
- `ListOfAllPropertyUseTypes`: All use types of the property.
- `LargestPropertyUseType`: Largest use type of the property.
- `LargestPropertyUseTypeGFA`: Floor area of the largest use type.
- `ENERGYSTARScore`: ENERGY STAR score of the property.
- `SiteEUI(kBtu/sf)`: Site Energy Use Intensity.
- `SourceEUI(kBtu/sf)`: Source Energy Use Intensity.
- `TotalGHGEmissions`: Total greenhouse gas emissions.
- `GHGEmissionsIntensity`: Greenhouse gas emissions intensity.

## Modeling

The modeling process involves the following steps:

1. **Data Preprocessing**:
    - Handling missing values.
    - Encoding categorical variables.
    - Normalizing/standardizing numerical features.

2. **Feature Selection**:
    - Using techniques such as PCA and feature importance to select relevant features.

3. **Model Training**:
    - Training various regression models to predict CO2 emissions and energy consumption.

4. **Model Evaluation**:
    - Evaluating models using cross-validation and performance metrics such as RMSE, MAE, and R².

5. **Hyperparameter Tuning**:
    - Tuning model hyperparameters to optimize performance.

## Results

The results of the analysis and modeling are presented in the form of:
- Performance metrics for the predictive models.
- Feature importance analysis.
- Insights and findings from the data analysis.

## Dashboard

A dashboard is created to visualize the results and provide an interactive interface for model interpretation. The dashboard includes:
- Visualizations of energy consumption and CO2 emissions.
- Interactive plots for feature importance and model performance.
- Prediction tool for estimating future emissions and energy consumption.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.