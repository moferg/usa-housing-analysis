# USA Housing Data Analysis Project

This project consists of a Jupyter notebook used to analyze housing data and a CSV file containing data about the USA housing market. The end goal is to use a Linear Regression model to predict housing prices based on features of the house, and along the way to compare the housing markets of comparable US cities. This project will also serve as the capstone project submission for the Code Louisville Data Analysis Course 2.

## Work In Progress

**This repo is actively being worked on.**

## Data

This project will use data sourced from a Kaggle dataset about homes for sale in the United States. The data is scraped from Craigslist every quarter or so, but at the time of this writing the most recent update to the dataset was performed on 6/17/2020. The dateset author did not state why the data has not been updated more recently, but this dataset should be fine for the analysis I want to perform. The original dataset can be [found here on Kaggle.](https://www.kaggle.com/austinreese/usa-housing-listings)

## Data Dictionary

This information can be found on the original Kaggle page, but I wanted to also include it in this README for easier access for both myself and anyone else using this project. The following is a list of columns and a description of the data within each column, copied directly from Kaggle:

| Column Title | Column Description|
|-----|-----|
|id | listing id|
|url | listing URL|
|region | craigslist region|
|region_url | region URL|
|price | rent per month|
|type | housing type|
|sqfoot | total square footage|
|beds | number of beds|
|baths | number of bathrooms|
|cats_allowed | cats allowed boolean (1 = yes, 0 = no)|
|dogs_allowed | dogs allowed boolean|
|smoking_allowed | smoking allowed boolean|
|wheelchair_access | has wheelchair access boolean|
|electric_vehicle_charge | has electric vehicle charger boolean|
|comes_furnished | comes with furniture boolean|
|laundry_options | laundry options available|
|parking_options | parking options available|
|image_url | image URL|
|description | description by poster|
|lat | latitude|
|long | longitude|
|state | state of listing|

## Project Requirements

The following is a list of the requirements laid out by Code Louisville that this project meets:

1. "Read data from an external file and use that data in your application."
    -This project reads in a CSV file obtained from Kaggle and uses the data in said file for analysis.
2. "Use a Jupyter notebook to document your data analysis."
    -The data analysis performed in this project is stored in a Jupyter notebook.
3. "Visualize data in a graph, chart, or other visual representation of data."
    -There are multiple charts created with the seaborn library in this project.
4. "Source data should not be modified/changed - clean data should be stored separately."
    -The original dataset, `housing.csv`, is unchanged. There is a shortened version of the data in `housing_trimmed.csv`, and a cleaned version in `housing_cleaned.csv`.