# USA Housing Data Analysis Project

This project consists of a Jupyter notebook used to analyze housing data and a CSV file containing data about the USA housing market. This project will also serve as the capstone project submission for the Code Louisville Data Analysis Course 2.

## Instructions

This repo is built using a number of libraries, the most important of which are geopandas, bokeh, and seaborn. Installing these libraries will install all other needed libraries by default. It is recommended to create a conda environment so as to not have to deal with any dependecies, especially with geopandas. You can do this by entering the following code into an anaconda command prompt:

`conda create -n geo-env`

`conda activate geo-env`

`conda install geopandas`

`conda install descartes`

`conda install bokeh`

`conda install seaborn`

Running these commands will create a virtual environment, in this case named geo-env, and install all necessary libraries. Afterwards, just open the Jupyter Notebook and run all cells.

## Data

This project will use data sourced from a Kaggle dataset about homes for rent in the United States. The data is scraped from Craigslist every quarter or so, but at the time of this writing the most recent update to the dataset was performed on 6/17/2020. The dateset author did not state why the data has not been updated more recently, but this dataset should be fine for the analysis I want to perform. The original dataset can be [found here on Kaggle.](https://www.kaggle.com/austinreese/usa-housing-listings)

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

1. Category 2: Utilize External Data
    * "Read data from an external file and use that data in your application."
        
        -This project reads in a CSV file obtained from Kaggle and uses the data in said file for analysis.
2. Category 3: Data Display
    * "Use a Jupyter notebook to document your data analysis."
        
        -The data analysis performed in this project is stored in a Jupyter notebook.
    * "Visualize data in a graph, chart, or other visual representation of data."
    
        -There are multiple charts created with the seaborn library in this project.
3. Category 4: Best Practices
    * "Source data should not be modified/changed - clean data should be stored separately."
        
        -The original dataset, `housing.csv`, is unchanged. There is a shortened version of the data in `housing_trimmed.csv`, and a cleaned version in `housing_cleaned.csv`.