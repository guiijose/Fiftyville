# Fiftyville Resolution

This repository contains my solution to the Fiftyville problem from CS50 2023. The problem involves solving a mystery using an SQLite3 database and Python in a Jupyter Notebook.

## Problem Description

Fiftyville is a fictional town with a database that contains various tables such as:
- **`crime_scene_reports`**: Contains reports of crimes, including the date, street, and description of the incident.

- **`interviews`**: Contains transcripts of interviews with various individuals, including their names and the date of the interview.

- **`atm_transactions`**: Contains details of ATM transactions, including account numbers, dates, locations, transaction types, and amounts.

- **`bank_accounts`**: Contains information about bank accounts, including account numbers, associated person IDs, and creation years.

- **`airports`**: Contains information about airports, including their abbreviations, full names, and the cities they are located in.

- **`flights`**: Contains flight details, including origin and destination airports, dates, and departure times.

- **`passengers`**: Contains details of passengers on flights, including passport numbers and seat assignments.

- **`phone_calls`**: Contains records of phone calls, including the caller, receiver, date, and duration of each call.

- **`people`**: Contains information about individuals, including their names, phone numbers, passport numbers, and license plates.

- **`bakery_security_logs`**: Contains logs from a bakery’s security system, including dates, times, activities, and license plates.

Using this database, the goal is to solve a mystery by writing SQL queries and analyzing the data.

## Solution Overview

My solution uses:
1. **SQLite3**: To query the database.
2. **Python**: To automate queries and process the results.
3. **Jupyter Notebook**: For an interactive environment to execute and visualize the solution.

## Files in this Repository

- **`main.ipynb`**: A Jupyter Notebook containing the full implementation of the solution.
- **`fiftyville.db`**: The SQLite3 database file provided for the problem.
- **`README.md`**: This file, describing the project and its implementation.
- **`table_fields.txt`**: All the information about all tables and all fields in the database.
- **`answers.txt`**: Answers for the problem.

## Key Steps in the Solution

1. **Understanding the Problem**:
   - Carefully read the problem statement and analyze the database schema.

2. **Writing SQL Queries**:
   - Constructed queries to extract relevant data (e.g., identifying individuals involved in suspicious activities).

3. **Automating Analysis**:
   - Used Python's `sqlite3` library to connect to the database, execute queries, and process results.

4. **Combining Insights**:
   - Integrated multiple queries and analyzed the results to deduce the solution to the mystery.

## Requirements

- Python 3.x
- SQLite3
- Jupyter Notebook
