# Restaurant Order Analysis 

This project contains a series of SQL queries designed to analyze restaurant order data. The analysis covers various aspects of restaurant operations, including menu details, order patterns, sales trends, and revenue insights.

## Table of Contents

1. [Introduction](#introduction)
2. [Database Schema](#database-schema)
3. [Queries](#queries)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

The goal of this project is to provide insights into the restaurant's operations by examining its menu items and order details. The SQL queries included in this project help to answer questions related to sales trends, popular items, revenue generation, and more.

## Database Schema

The project assumes the existence of two primary tables:

1. **menu_items**
   - `menu_item_id`: The unique identifier for each menu item.
   - `item_name`: The name of the menu item.
   - `category`: The category to which the menu item belongs (e.g., Italian, Chinese, etc.).
   - `price`: The price of the menu item.

2. **order_details**
   - `order_details_id`: The unique identifier for each order detail.
   - `order_id`: The unique identifier for each order.
   - `item_id`: The unique identifier for each menu item ordered.
   - `order_date`: The date and time when the order was placed.
   - `quantity`: The quantity of the menu item ordered.

## Queries

The SQL file (`restaurant_order_analysis.sql`) contains the following queries:

1. **Menu Analysis**
   - View all menu items.
   - Count the total number of menu items.
   - Identify the least and most expensive items.
   - Count the number of Italian dishes.
   - Identify the least and most expensive Italian dishes.
   - Count the number of dishes in each category.
   - Calculate the average price within each category.

2. **Order Analysis**
   - View all order details.
   - Determine the date range of orders.
   - Count the total number of unique orders.
   - Count the total number of items ordered.
   - Identify orders with the most items.
   - Count the number of orders with more than 12 items.

3. **Combined Analysis**
   - Combine menu items and order details to view all details.
   - Identify the least and most ordered items and their categories.
   - Find the top 5 orders that spent the most money.
   - View the details of the highest spend orders and the items purchased.

4. **Sales Trends**
   - Analyze sales trends by hour of the day.

## Usage

To use the SQL queries in this project:

1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/YOUR_USERNAME/Restaurant-Order-Analysis.git
