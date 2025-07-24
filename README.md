# data-analysis

## Table of Contents

[Project Overview](#project-overview)

[Data Sources](#data-sources)

### Project Overview

This data analysis project aims to provide insights into the sales performance of an e-commerce company over the past year. By analyzing various aspects of the sales data,                                                                                                      we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "customers_10000.zip" file, containing detailed information about each sale made by the company.

### Tools
 
- Excel - Data Cleaning
  - [Download Here](https://microsoft.com)
- SQL Server - Data Analysis
- PowerBI - Creating Reports

### Data Cleaning/Preparation

In the initial data preparation phase we performed the following tasks:

1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

 -What is the overall sales trend?
 
 -Which products are top sellers?
 
 -What are peak sales periods?

### Data Analysis

Include some interesting code/features you worked with (Sub query, CTE, window function)
        
        "`"(symbol is next to the #1 on the keyboard, called the backclick)
```sql
SELECT * FROM table1
WHERE CONDITION = 2;
```
        
### Results/Findings

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product category A is the best performing in terms of sales and revenue.
3. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations

Based on the analysis, we recommend the following actions:

-Invest in marketing and promotions during peak sales seasons to maximize revenue.

-Focus on promoting and expanding products in Category A.

-Implement a customer segmentation strategy to target high - LTV customers effectively.

### Limitations

I had to remove all the zeroes from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a 
few outliers even after the omissions but even then we can still see there is a positive correlation betwee both budget and the number of votes with revenue.

### References

1. SQL for Businesses by werty
2. [Stack Overflow](https://stack.com)
