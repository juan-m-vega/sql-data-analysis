### SQL Data Analysis

As part of the Data Science Immersive training at General Assembly, I had the opportunity to use multiple tables created within a database to join tables, summarize and filter data, aggregate data, use Common Table Expressions (CTEs), Window Functions, and more.

General Assembly provided the data and questions as a resource for students to learn, and the answers to these questions in the notebook `ladder-challenge-sql` are the product of my work.
This sample project is included for demonstration of previous SQL experience and work.

The queries in this repository are created using the following tables, which include the following columns:
* `Pets`: lists name, sex, species, and age of a collection of pets
* `employees_null` and `employees`: lists information of employees of a corporation including employee ID, first name, last name, job title, salary, and start date
* `transactions`: order ID, customer name, unit price, quantity sold, order date, and employee ID
* `yum`: stock data for `Yum! Brands, Inc.` from 2015 to 2019 including date, opening price, high, low, closing price, and trading volume

To execute this project, the user may need to:
* Install the `sqlalchemy` library using `!conda install sqlalchemy`
* Install the `psycop2` using `!conda install psycop2`
* Install `psycopg2-binary` using `!pip install psycopg2-binary`
