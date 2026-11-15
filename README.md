Customer Delivery Database

## Overview

Customer Delivery Database is a Python project that connects to a MySQL database.
The program can be used to add and display customer information and view delivery information stored in the database.

## Project Structure

The project contains three main classes:

- **Database** : connects the program to the MySQL database.
- **Customer** : adds and displays customer records.
- **Delivery** : displays delivery records.

The Customer and Delivery classes both use the database connection created by the Database class.

## Requirements

To run the project you will need:
- Python 3
- MySQL
- mysql\-connector\-python

Install the MySQL connector using: pip install mysql\-connector\-python

## How to Run

1. Clone or download the repository.
2. Make sure Python and MySQL are installed.
3. Install the mysql\-connector\-python package.
4. Make sure the customer and delivery tables have been created in the database.
5. Update the database connection details if needed.
6. Run the Python program.
7. Use the program options to add or view customer and delivery records.

## Current Design

The Database class handles the connection to MySQL.
The Customer class uses this connection to add and view customer data.
The Delivery class uses the same connection to view delivery data.
Using separate classes keeps  code organised and makes it easier to understand what each part of the program does.

## Known Limitations
The project currently has a few areas that could be improved:

- Some methods print results instead of returning them.
- Database cursors are not always closed.
- There is limited error handling for database connection issues.
These could be improved in future development.

## Intended Audience
This README is for developers, testers or anyone reviewing the project. It explains what the project does, how it works and how to run it.

## Future Improvements
Future improvements could include better error handling, automated testing and more input validation.

