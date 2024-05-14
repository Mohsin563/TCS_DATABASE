
# TCS (Tranzuam Courier Services) Database

This repository contains SQL scripts to set up a database for managing transportation and courier services for TCS (Transportation & Courier Services).

## Description

The database schema consists of several tables to manage customers, orders, payments, shipments, branches, departments, and employees. Below is a brief overview of each table:

- **customer**: Stores information about customers such as their name, contact details, and address.
- **orders**: Contains details of orders placed by customers including order type, weight, receiver address, and order date.
- **payment**: Manages payment information including payment type, date, status, and charges.
- **shipment**: Tracks shipment details such as status, dispatch date, expected delivery date, and current location.
- **branch**: Stores information about different branches of TCS including the branch name, manager ID, location, and contact details.
- **department**: Manages department details within branches including the department name, branch ID, and manager ID.
- **employee**: Stores employee information such as name, email, contact, job title, start date, salary, branch ID, and department ID.

## Setup

1. **Database Creation**: Execute the SQL script provided in this repository to create the necessary tables and populate them with sample data.
   
2. **Usage**: After setting up the database, you can use it to manage transportation and courier services for TCS.

## SQL Scripts

- **tcs_database.sql**: Contains SQL commands to create tables and insert sample data into them.
- **queries.sql**: Contains sample queries to retrieve information from the database.

## Contributors

- [MOSHIN RAZA & MUJEEBULLAH] 

