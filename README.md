# Company Management System

# Description

This project demonstrates a simple data management system using SQLite and pandas, with a focus on creating and interacting with databases. It includes the creation of tables, insertion of data, and usage of the pandas library to handle Excel data and interact with an SQLite database using SQLAlchemy.


# Requirements

  Python 3.x
  SQLite3
  Pandas
  SQLAlchemy

# Installation

  Clone the repository:

  bash

git clone https://github.com/yourusername/yourproject.git

Install the required Python packages:

bash

  pip install -r requirements.txt

# Usage

Open the main.py file.

Update the SQLite database path:

python

conn = sqlite3.connect('your_database_path.db')

Run the script:

bash

python main.py

# Database Structure
## Manager Table

MANAGER_ID INTEGER (Primary Key)
MANAGER_FNAME TEXT
MANAGER_SNAME TEXT
COMPANY_ID INTEGER
JOIN_DATE TEXT

## Companies Table

COMPANY_ID INTEGER (Primary Key)
COMPANY_NAME TEXT

## President Table (example)

PRESIDENT_ID INTEGER (Primary Key)
AGE INTEGER
NAME TEXT
HEIGHT INTEGER

## Data Insertion

Managers data is inserted into the Manager table.
Companies data is inserted into the Companies table.
President data is inserted into the president table.

## Pandas Integration

The project includes integration with the Pandas library for Excel data manipulation and SQLite database interaction. Data from an Excel file is read into a Pandas DataFrame and then stored in an SQLite database.
Contributing

Feel free to contribute to the project by opening issues or creating pull requests. Your feedback and suggestions are highly appreciated.
License

This project is licensed under the MIT License.
