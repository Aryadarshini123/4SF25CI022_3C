# Zomato Restaurant Data Analysis

## Project Overview
This project analyzes the Zomato Bangalore Restaurants dataset using Python and Pandas. The objective is to perform data transformation, handle missing values, generate meaningful insights, and visualize the findings.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset contains information about restaurants, including:
- Restaurant names
- Online ordering availability
- Table booking availability
- Restaurant ratings
- Votes
- Locations
- Cuisines
- Approximate cost for two people

## Tasks Performed

## 1. Dataset Reading
Loaded the CSV dataset using Pandas.

## 2. Data Understanding
Examined dataset dimensions, column names, data types, and statistical descriptions.

## 3. Data Transformation
- Removed unnecessary columns.
- Renamed column names.
- Converted restaurant ratings into numerical values.
- Converted cost values into numerical format.
- Created price categories.

## 4. Null Value Handling
- Identified missing values.
- Applied mean imputation to numerical columns.
- Handled categorical missing values using mode   imputation and an Unknown category.

## 5. Insight Generation
- Identified top restaurant locations.
- Calculated average restaurant ratings.
- Analysed highly rated restaurants.
- Compared average costs across restaurant types.
- Examined online ordering availability.

## 6. Data Visualization
Created bar charts, histograms, pie charts, and scatter plots to visualize the findings.

## Conclusion
This project demonstrates the use of Python and Pandas for data cleaning, transformation, missing value handling, exploratory data analysis, and visualization.

## Repository Contents
- `Zomato_Data_Analysis.ipynb` – Python analysis notebook.
- `zomato.csv` – Original dataset.
- `README.md` – Project documentation.

## Dataset
The dataset used for this project is the Zomato Dataset downloaded from Kaggle.

**Source:** https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset

The dataset is not uploaded to this repository because of its large file size. Download it from the above link and place the CSV file in the same folder as the Jupyter Notebook before running the code.