# matplotlibchallenge
OPEN THE JUPYTER SOURCE FILE FOR THE WORK. 


Project Overview

This project analyzes data from a pharmaceutical study conducted by Pymaceuticals Inc. The study examines the effectiveness of various drug regimens on squamous cell carcinoma (SCC) in mice. The primary objective is to assess the impact of different treatments, particularly Capomulin, on tumor volume reduction.

Dataset

The dataset consists of two CSV files:

Mouse_metadata.csv: Contains information about the mice, including their ID, drug regimen, sex, age, and weight.

Study_results.csv: Includes tumor volume measurements over time for each mouse under different drug regimens.

Analysis Performed

Data Cleaning

Merging the datasets.

Identifying and removing duplicate records.

Checking the number of unique mice.

Summary Statistics

Calculating mean, median, variance, standard deviation, and SEM of tumor volumes for each drug regimen.

Data Visualization

Bar plots showing the total number of observations for each drug regimen.

Pie charts illustrating the gender distribution of the mice.

Box plots displaying the distribution of final tumor volumes across selected treatments.

Line plot of tumor volume over time for a mouse treated with Capomulin.

Scatter plot of mouse weight vs. average tumor volume for Capomulin.

Statistical Analysis

Computing the correlation coefficient between mouse weight and tumor volume.

Performing a linear regression analysis to understand the relationship between these variables.

Technologies Used

Python

Pandas

Matplotlib

Scipy

How to Run

Ensure that the dataset files (Mouse_metadata.csv and Study_results.csv) are placed inside the data/ directory.

Run the provided Python script to execute the data analysis and generate visualizations.

Key Findings

Capomulin and Ramicane showed the most promising results in reducing tumor volume.

There is a strong positive correlation between mouse weight and tumor volume under the Capomulin regimen.

Tumor volume trends can be visualized effectively using time-series plots for individual mice.
