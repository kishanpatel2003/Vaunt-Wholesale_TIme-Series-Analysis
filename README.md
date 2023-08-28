# Vaunt Wholesale Time Series Analysis
A deep analytical dive into my Amazon FBA business Vaunt Wholesale LLC for the first 6 months of 2023. Let's explore what's working and where the money is flowing!

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
Concatenated reports from January-June produced by Amazon Seller Central for FBA owners into a single dataframe. These reports provide a complete accounting of all products sold from 1/1 - 6/30 and information such as product name, ASIN, quantity, cost, shipping level (normal, expedited, 2-day, etc.), shipping state, etc. Performed data preprocessing tasks, including handling missing values and ensuring data consistency by creating my own dictionary of accepted categorial variables. Raw spreadsheets can be accessed in the RawData folder.

## 2. Examining Revenue by State
![Image Alt Text](/Visualizations/geopanda.jpeg)
This choropleth map showcases Vaunt Wholesale's revenue distribution across different U.S. states. Each state is color-coded based on the total revenue generated from customer purchases. The map provides a visual snapshot of the business's regional revenue contributions, aiding in identifying key areas of business. No surprise here: CA, TX, FL, and NY dominate sales.

## 3. Analyzing Revenue over Time
![Image Alt Text](/Visualizations/RevenueLine.jpeg)
In this graph, we delve into the daily revenue trends of Vaunt Wholesale over time. By plotting actual daily revenue values and overlaying a 7-day moving average, we gain insights into the overall revenue trajectory while smoothing out short-term fluctuations. This visualization offers a clearer perspective on revenue trends and potential patterns that may emerge in business operations, revenue blurred for privacy.

## 4. Exploring Sales Volume over Time
![Image Alt Text](/Visualizations/VolumeLine.jpeg)
This chart offers an exploration of the daily sales volume trends at Vaunt Wholesale. By showcasing both the raw daily sales volume and the 7-day moving average, we gain insights into the variations and trends within sales over time. The visual representation of these patterns aids in understanding the business's sales performance dynamics. This visualization suggests a clear correlation with revenue.

## 5. Determining Vaunt's Top Products in the First Half of 2023
![Image Alt Text](/Visualizations/TopProducts.jpeg)
Delving into Vaunt Wholesale's product revenue distribution, this visualization spotlights the top 10 highest-grossing products during Q1 and Q2. The names of these products have been abbreviated for clarity, revenue blurred for privacy. The chart's layout enhances readability, making it easier to identify the products that significantly impacted revenue during this period. Vital Proteins all the way!

## 5. What Shipping Service is Most Selected by Customers?
![Image Alt Text](/Visualizations/Shipping.jpeg)
Ever wonder what type of shipping most people opt for on Amazon? Should come as no surprise that Standard is the most popular and Prime's 2-day ranks next.

# Summary
This project takes a close look at Vaunt Wholesale LLC's Amazon FBA business for the first half of 2023. With detailed data analysis and cool visuals, we look into revenue distribution, trends, sales volume, top products, and shipping choices.
