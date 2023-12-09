Exploratory Data Analysis - Customer Loans in Finance

The aim of this project is to perform Exploratory Data Analysis (EDA) on a portfolio of loans. Using statistical approaches and visualization methods, our goal is to reveal patterns, trends, and irregularities in the dataset. Furthermore, we will prepare the data for ML algorithms by handling outliers and addressing skewness. Additionally, we will create visualizations of future payments and investigate potential connections between user data parameters and instances of unsuccessful loan repayments.

The overarching objective is to enable the business to improve decision-making in key areas such as risk assessment, return evaluation, and approval processes. This will be achieved by leveraging more precise insights derived from the analysis of the data.

Modules

*./format.py* Class to convert columns into correct format such as categorical columns, more efficient data types and numerical columns that are better fit into numericals, as well as dates.

*./info.py* Provides information about the shape of the data, skewness numericals, missing data and general statistics where needed.

*./plotter.py* Provides visualisation methods for the data such as histograms, KDE, qq_plot and ability to do so across multiple columns.
 *./transform.py* Responsible for imputation and transformation of data to prepare for more ML applications via creating a normal distribution.

 
Installations
 pip install -r requirements.txt
 pip install pyYAML

Running Instructions
 Run main.ipynb 