# Exploratory Data Analysis Project on Electric Vehicle Data
### Project Overview
This project involves the analysis of electric vehicle (EV) data to derive meaningful insights and support better decision-making. The analysis focuses on understanding trends in electric vehicle types, exploring pricing patterns, and identifying the factors that may influence the adoption of electric vehicles. The project also visualizes key metrics to make data-driven insights easily understandable.

### Project Objectives
#### Exploratory Data Analysis (EDA):
* Perform both univariate and bivariate analysis to explore the characteristics of the dataset.
* Understand the trends in electric vehicle types, electric range, and pricing.
* Identify outliers and clean the dataset to improve the quality of insights.
#### Data Visualization:
* Create various plots (e.g., stacked bar plots, heatmaps, scatter plots) to illustrate key findings.
* Use visual tools like choropleth maps and animated bar charts to present data in an engaging way.
#### Outlier Handling:
* Remove outliers from the dataset, focusing on specific columns such as electric range, base MSRP, and model year, to enhance data accuracy.
### Dataset
The dataset used for this project contains information about electric vehicles, including:
* Model Year
* Electric Vehicle Type
* Electric Range
* Base MSRP
* CAFV Eligibility
* Vehicle Location
* Electric Utility
And other relevant features.
### Tasks and Methods
#### Task 1: Exploratory Data Analysis (EDA)
* Univariate Analysis: Analyzed each variable individually using histograms, box plots, and summary statistics.
* Bivariate Analysis: Explored relationships between variables using scatter plots, stacked bar plots, and heatmaps.
* Outlier Detection and Removal: Identified outliers in specific columns (e.g., base MSRP, electric range) and cleaned the data to improve accuracy.
#### Task 2: Data Visualization
* Choropleth Map: Displayed the distribution of EVs across different locations using plotly.express.
* Animated Bar Chart: Showed the growth of different EV makes over time using an animated racing bar chart.
#### Task 3: Outlier Handling
* Cleaned the dataset by removing outliers for more accurate analysis:
* Removed data points with base MSRP = 0 or greater than $175,000.
* Removed PHEV entries where electric range exceeded 50 miles.
* Filtered out models with model years before 2010.
### Key Visualizations and Insights
* Box Plots: Showcased variations in electric ranges between different EV types and highlighted outliers that were later addressed.
* Stacked Bar Plots: Demonstrated the distribution of CAFV eligibility across EV types, which helps understand the market adoption of cleaner vehicles.
* Heatmaps: Provided a clear view of the relationship between EV types and CAFV eligibility, highlighting areas for improvement in policy or marketing.
* Scatter Plot: Explored the relationship between electric range and base MSRP, showing how range capabilities impact vehicle pricing.
* Correlation Matrix Heatmap: Identified the correlation between numerical features such as model year, electric range, and base MSRP.
* Animated Choropleth Map: Visualized the number of EVs based on location, showing regional trends and areas with high EV adoption.
* Racing Bar Plot: Animated growth of different EV makes over the years, showing brand dominance in the EV market.
### Tools and Technologies
* Programming Language: Python
* Libraries:
  * pandas for data manipulation and cleaning
  * seaborn and matplotlib for data visualization
  * plotly.express for interactive and animated visualizations
  * numpy for numerical operations
  * bar_chart_race for animated bar charts
