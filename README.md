# Pizza Sales Data Analysis

## About

This project aims to explore pizza sales data to understand top-performing products, sales trends, and customer behavior. The goal is to analyze how sales strategies can be improved and optimized. The dataset includes detailed transaction records from different pizza orders.

## Dataset Structure

We have used 4 differernt datasets here. The dataset consists of multiple tables that store information related to pizza sales, including:

- **Orders**: Records of customer purchases, including order timestamps.
- **Order Details**: Itemized details of each order, including pizza types and quantities.
- **Pizzas**: Information on available pizza varieties, pricing, and sizes.
- **Pizza_types**: Contains information about differnet types of pizzas, which category they belong, and ingredients.

## Key Analyses

- **Product Analysis**: Evaluating different pizza types, identifying best-selling pizzas, and determining which products need improvement.
- **Sales Analysis**: Examining sales trends, seasonal variations, and the impact of promotions.
- **Customer Analysis**: Understanding customer purchase patterns, segmenting customers, and analyzing profitability.

## Approach Used

- **Data Wrangling**: Cleaning and preprocessing data to handle missing values and inconsistencies.
- **Feature Engineering**: Creating new features such as the busiest time of day, day of the week, and monthly sales trends.
- **Exploratory Data Analysis (EDA)**: Analyzing key performance indicators and deriving actionable insights.

## Business Questions to Answer

Basic:
Retrieve the total number of orders placed.
Calculate the total revenue generated from pizza sales.
Identify the highest-priced pizza.
Identify the most common pizza size ordered.
List the top 5 most ordered pizza types along with their quantities.


Intermediate:
Join the necessary tables to find the total quantity of each pizza category ordered.
Determine the distribution of orders by hour of the day.
Join relevant tables to find the category-wise distribution of pizzas.
Group the orders by date and calculate the average number of pizzas ordered per day.
Determine the top 3 most ordered pizza types based on revenue.

Advanced:
Calculate the percentage contribution of each pizza type to total revenue.
Analyze the cumulative revenue generated over time.
Determine the top 3 most ordered pizza types based on revenue for each pizza category.
## Usage

1. Clone this repository.
2. Load the dataset into a SQL database.
3. Execute analytical queries to extract meaningful insights from the data.

## License

This project is open-source and available for public use.

