

Scope:

Data analysis & visualization sales dataset with Python using Matplotlib, Pandas (Jupyter Notebook).

Using Python, the following analysis of 'Sales.csv' are done.

1: Total sales

2: Total sales by month

3: Total sales per zip code

4: Breakdown of sales by teaching hospital vs non-teaching hospital


Data Source:

sales.csv


Objective:

Sales data from csv file is read and pandas dataframe is created.
Provided information about the dataset using describe() & info().
Calculations are performed on Total Sales.
Total Sales by month is calculated by Group by. A Bar chart is generated for visualization.
Total Sales per zipcode is calculated by Group by and pivot table. A Bar chart is generated for visualization.
A field is created to differenciate the Teaching vs Non Teaching Hospital type.
A pivot table is generated to display the break down for the hospital type.
A stacked bar graph is generated for visualizing the break down of the Teaching and Non Teaching Hospital Type.
To create a geo visualization for the total sales across zipcode,  notebook heat_map_zipcode is created. Here top ranking zipcodes sorted with maximum total sales are stored. Then these zipcodes are coverted to latitude and longitide. Google heat map is created to visualize the spread of total sales weightage.


Steps To Run:


For this demonstration, I am using the Jupyter Notebook, open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.


Step 1:
Create a virtual enviroment and install dependencies by running requirements.txt.
$ pip install virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt


Step 2:

Run the script.
$ jupyter notebooks

1. Sales_Analysis - For all the calculations and charts/graphs.


Step 3:

I have used my google key in the config.py. For secuirity, I have encrypted as google key. Proper google key should be updated in the config.py

Run the script.
$ jupyter notebooks

1.Heat_map_zipcode- For the google heatmap for the zipcode with the weightage of Total Sales.

