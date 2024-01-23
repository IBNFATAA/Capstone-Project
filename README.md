# Pizza Sales Analysis

![pizza-store-](https://github.com/habeebsalaudeen/Capstone-Project/assets/97491265/fa60115a-398c-4112-aed8-0c0e5fb3b49a)


## Introduction
This is a Power BI projecct on sales analysis of a fictitious pizza place called called **Pizza Sales Store**.
The project is to analyze and derive insights to answer crucial questions and help the company make data driven 
decisions.
**_Disclaimer_** : All datasets and reports do not specifically point to any company, institution or country, but just a hands on data given by Scenario Academy for Intern Data Analyst to show, analyze and give insightful decision through creating amazing and beautiful report using Power BI.

## Problem Statement
1. How many customers do we have each day? Are there any peak hours? 
2. How many pizzas are typically in an order? Do we have any bestsellers?
3. How much money did we make this year? Can we identify any seasonality in the sales?
4. Are there any pizzas we should take off the menu, or any promotions we could leverage?

## Skills / Concepts Demonstrated
- Data Modeling and Relationships
- DAX (Data Analysis Expressions)
- Aggregation Techniques
- Filters and Slicers
- Buttons
- Word wrapping

## Modelling
In constructing our sales analysis model in Power BI, I took a hands-on approach, personally deriving and connecting 
various components to ensure a comprehensive and tailored solution. 

![Report](https://github.com/habeebsalaudeen/Capstone-Project/assets/97491265/588278ad-c238-4a9f-bdc6-156d286d7bb3)


The model is a star schema.
There are 3 dimension tables and 1 fact table and also a **Dax measure table** containg all the dax measures. The dimension are all joined to the fact table with a one-to-many relationship.

## Visualization:

The report comprises 1 page only with fascinating and beautiful underdable visuals:
1. Pizza Sales report 

You can interact with the report {here} 
(https://app.powerbi.com/groups/me/reports/985652d7-4104-471a-909b-d14be913bd92/ReportSection?experience=power-bi)

### Bit By Bit Explanation Of Visuals
In this Power BI sales analysis, I skillfully crafted a dynamic and comprehensive model. I implemented advanced measures, creating slicers for both years and category to ensure seamless interaction with the report.

### Header Visual
<img width="615" alt="Title_DateSlicer" src="https://github.com/habeebsalaudeen/Capstone-Project/assets/97491265/9b8af064-93f2-41af-bbad-89627f22ed5d">
This visual has a captivating rectangle fill blue color that contain the image of a slicer to the left butressing our visualization for any layman to denote we are analyzing something related to pizza, the topic also for more emphasis, and date slicer to make our interaction with the report very seamless and effortless.

### Best And Worst Sellers
<img width="275" alt="BEST_Worst_Pizza" src="https://github.com/habeebsalaudeen/Capstone-Project/assets/97491265/629a4928-7ca2-414c-b170-d742fc452a34">
The two stacked bar charts used here make it easy to recognize the piza types doing well the most**(Thai Chicken)** that it sales be intensify and the one that it sales have to be less produced or even put off sales in the future **(Brie Carre Pizza)**. this visual uses bars to show profit generated by each of the pizza types and filters for easy comprehension of denoting only the best top 5 pizza and the worst bottom 5.

### Hour_Category_Size
<img width="330" alt="Hour_Category_Size" src="https://github.com/habeebsalaudeen/Capstone-Project/assets/97491265/b952443e-3d7c-43f8-8f72-1ad22640a643">
line chart illustrate the peak hours that we have more pizza sold and in this case(12:00PM-1:00PM). Also doughnut chars is used for both total piza sold by category and the highest being(Classic), and total piza sold by size and the highest being(Large).

### Final Pizza Sales Report
![Pizza_Sales_Report](https://github.com/habeebsalaudeen/Capstone-Project/assets/97491265/fc24fa4b-fb93-4fd3-8c59-1a04ea2a771d)

## Conclusion and Recommendation
The insights generated from the report shows:
- The average number of customers per day is 60, and 12 p.m. to 1 p.m. is the peak hour of sale.
- There is an average of 2 pizzas in an order, and the best-selling pizza is the Thai Chicken Pizza.
- The total profit made this year is $817.86K, and people are more interested in Thai chicken pizza.
- We should remove Brie Carre Pizza from the menu since it is the least popular pizza.
