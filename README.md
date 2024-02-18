# VeggieMart-Data-Modelling-Project

# VeggieMart Data Modeling Project

## Introduction

Imagine that we are helping a grocery store, VeggieMart, model their data for reporting purposes. The leadership team at VeggieMart is particularly interested in gaining insights relating to the following items:

- Stores
- Regions
- Managers
- Employees
- Transactions

Assume the following constraints:

- All managers are employees, but not all employees are managers.
- Each store has only one manager.
- Employees have a unique role at a store of either "manager" or "store worker".
- A manager can lead multiple stores, but store workers can only work at one store.
- Transactions can have multiple items.
- Transactions occur only in USD.

## Directions

Using Google Sheets, create an Enterprise Bus Matrix for business processes and dimensions related to the project prompt. Within the same worksheet, below the bus matrix, create table documentation for the fact and dimension tables that relate to the project prompt. As you build out these resources, consider the questions you want may want this data model to answer, for example:

- How many stores exist in each region?
- Which store had the highest revenue last year?
- What store(s) is a manager currently assigned to?
- How many employees work at each store?
- Which employees are working over 40 hours per week?
- Which stores have the highest average transaction amount?
- What percent of transactions included at least one non-food item?
- When a store manager goes from managing one store to two stores, how is each store's revenue impacted?
- Anything else that seems relevant or interesting.

Try to include at least 4 business processes that a grocery store would engage in and at least 5 dimensions that would be relevant in analysis.

## Bonus #1

Write some pseudo SQL queries based off the tables you documented that would give valuable insights to the VeggieMart team.

## Bonus #2

Within Google Sheets, create a table that corresponds to each dimension and fact you documented, and populate those tables with 5-10 records of sample data. What are the possible values that could be populated? Can a value be null? How would that impact how the data should be queried?
