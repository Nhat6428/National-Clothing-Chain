# Market Performance Analysis - National Clothing Store Chain

## 📌 Introduction

This report provides a detailed analysis of the market performance of a national clothing store chain, focusing on key metrics such as customer ratings, average income by state, total revenue, and demographic trends. The data is presented through various charts and graphs, each offering insights into different aspects of the business.

## 📊 Data Sources

### Data Overview
The provided data includes multiple tables and information related to a national online clothing store chain. The main tables include:

- Customer List: Contains customer information such as ID, name, date of birth, age group, and purchase history.

- Incomes by State: Provides estimated income, income categories, and percentage rates by state.

- Product Inventory: Lists current products, prices, customer ratings, return rates, and stock quantities.

- Sales List: Includes information about key industries, industry population, and total purchases by state.

## 🛠️ Data Processing

The data was cleaned and transformed for analysis:

- Product Inventory: Cleaned using the “Split Column by Delimiter” function in Power Query to separate columns, rename, and change data types appropriately.

- Purchase History: Cleaned using the “Unpivot” function to convert date columns into two columns (Attributes and Values), then renamed and changed data types.

## Data Relationships

Relationships were created between necessary tables to support analysis. Key tables were linked through primary and foreign keys, enabling efficient querying and analysis.

![Image](https://github.com/user-attachments/assets/f2cf9daa-ac0b-43de-b6a4-b0c58055ec36)

## 📈 Analysis

### 1. Overview

![Image](https://github.com/user-attachments/assets/d3da39a3-f2d0-4949-965c-cb8c0cb8d8b6)

####  Top 10 States by Total Transactions  

- Observation: California leads with the highest total transactions, followed by Texas and Illinois. These states significantly outperform others.

- Conclusion: California is a key market; marketing resources should be focused on this region to optimize sales.

####  Top 10 States by Average Income  

- Observation: District of Columbia has the highest average income, followed by New Jersey and Maryland. These states have significantly higher incomes than others.

- Conclusion: High-income states such as the District of Columbia and New Jersey are ideal targets for premium products; advertising should target high-income groups.

####  Total Population by State 

- Observation: California and Texas have the largest populations, followed by Florida and New York. These states have large market potential due to high population.

- Conclusion: Highly populated states like California and Texas should be prioritized in marketing strategies to leverage market potential.

####  Inventory Quantity by Rating

- Observation: Products with higher ratings tend to have higher prices and lower stock levels, indicating that high-quality products are in demand and can potentially be priced higher for profit optimization.

- Conclusion: Consider raising prices for highly-rated products to optimize profitability.

### 2. Customer Insights

![Image](https://github.com/user-attachments/assets/c42b1cb0-3251-4b06-9bd1-527a0d18f2e6)

####  Customer Age Distribution  

- Observation: The "Middle Aged" group accounts for the largest proportion, followed by "Young Adult" and "Old Aged." The "Middle Aged" group also has the highest average purchase value.

- Conclusion: Marketing strategies should focus on the "Middle Aged" group as they are the main customer base with high purchasing value.

####  Total Purchases by State  

- Observation: California and Texas have the highest number of purchases, followed by Florida and New York. These states significantly outperform others.

- Conclusion: Focus marketing resources on states with high purchase volumes like California and Texas.

####  Purchase Trends Over Time  

- Observation: Sales increase steadily over time, especially during the year-end months (Nov 2020 - Jan 2021), indicating a peak shopping season.

- Conclusion: Intensify marketing campaigns during the year-end months to capitalize on the peak shopping season.

### 3. Product Analysis

![Image](https://github.com/user-attachments/assets/bb3aa83b-b535-4ac2-adb7-68a0570e6af1)

####  Relationship Between Ratings and Return Rates

- Observation: Products with lower ratings tend to have higher return rates. The correlation coefficient is 0.69, indicating a fairly strong relationship between rating and return rate.

- Conclusion: Improve the quality of low-rated products to reduce return rates and increase customer ratings.

####  Top 5 Highest and Lowest Rated Products

- Observation: "Chronograph Watch" has the highest rating, while "Winner Gloves" has the lowest. Highly-rated products often have higher prices.

- Conclusion: Improve the quality of low-rated products and maintain the quality of highly-rated ones.

####  Workforce Population in Key Industries by State

- Observation: California and Texas have the largest workforce populations in key industries. These states offer high market potential due to their industrial workforce.

- Conclusion: Focus marketing efforts on states with large key industry workforces to increase sales.

### 4. Conclusion

This report provides an overview of the market performance of the national clothing store chain. The charts and analyses highlight areas for improvement and opportunities for growth and expansion. Focusing on high-income states, improving product quality, and optimizing marketing strategies based on age groups will help increase revenue and customer satisfaction.
