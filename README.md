# Vaunt Wholesale Time Series Analysis
A deep analytical dive into my Amazon FBA business Vaunt Wholesale LLC for the first 6 months of 2023

# Project Steps
- Compiled a dataset (***~9000 data points***) by extracting/concatenating business reports generated monthly by Amazon
- Conducted thorough data cleaning and preprocessing
- Examined revenue distribution by state 
- Explored the revenue trends over time
- Analyzed the sales volume patterns over time
- Identified the top-performing products
- Investigated the distribution of shipping service levels

Languages: Python

Packages: pandas, numpy, geopandas, matplotlib

## 1. Data Collection and Preprocessing
Concatenated reports from January-June produced Amazon Seller Central for FBA owners into a single dataframe. These reports provide a complete accounting of all products sold from 1/1 - 6/30 and information such as product name, ASIN, quantity, cost, shipping level (normal, expedited, 2-day, etc.), shipping state, etc. Performed data preprocessing tasks, including handling missing values and ensuring data consistency by creating my own dictionary of accepted categorial variables

## 2. Examining Revenue by State
![Image Alt Text](/Visualizations/geopanda.jpeg)
This choropleth map showcases Vaunt Wholesale's revenue distribution across different U.S. states. Each state is color-coded based on the total revenue generated from customer purchases. The map provides a visual snapshot of the business's regional revenue contributions, aiding in identifying key areas of business.
