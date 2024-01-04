**Deciphering Electric Energy Pricing in U.S. Households**

***Research question***

What are the key factors influencing the residential energy price (Cents/kWh) in various states over time, considering the mix of energy sources and consumption patterns?

***Target Variable (1)***

- Residential Price Cents/kWh

***Input Variables (8)***

- Total Revenue Thousand Dollars
- Generation_from_Coal_MWh
- Generation_from_Petroleum_MWh
- Consumption_Coal (Short Tons)
- Consumption_Petroleum (Barrels)
- Cushing, OK Crude Oil Future Contract 1 (Dollars per Barrel)
- Coal_Price
- Residential Customer Count


***Data Handling***
The study involves extensive data handling steps, including loading various datasets related to energy, formatting and merging them, and data cleaning.
Formmatted data is loaded into Data/Formatted/ folder.

***Analysis and Modeling***
The document covers exploratory data analysis, including checking correlations, temporal and geographical trends, and consumption patterns. It also includes outlier detection and implements several predictive models like Linear Regression, Random Forest, XG Boosting, and more.
