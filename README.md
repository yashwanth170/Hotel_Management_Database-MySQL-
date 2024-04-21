# Hotel Management Database

This repository contains a MySQL database for a hotel management system. The database is fully normalized and incorporates various types of relations. In addition to normalization, the database utilizes triggers, functions, and other MySQL features to enhance functionality and maintain data integrity.

## Contents

- SQL Dump File: The SQL dump file (`hotel_database_dump.sql`) is included in the repository. You can use this file to import the database schema and sample data into your MySQL environment.

## Database Schema Visualization

![Schema Visualization](Schema.png)

The `Schema.png` image provides a visual representation of the database schema, making it easier to understand the structure and relationships between different tables.

## Features

- Normalization: The database schema follows the principles of normalization to minimize redundancy and maintain data integrity.
- Relationships: Various types of relationships such as one-to-many, many-to-many, etc., are established between tables to efficiently represent data associations.
- Triggers: Triggers are implemented to automatically perform actions, such as updating other tables or enforcing business rules, when specific events occur in the database. Ex: Billing Table
- Functions: MySQL functions are utilized to encapsulate logic that can be reused across different parts of the database.

## Usage

1. **Importing the Database**: Use the SQL dump file to create the database schema and populate it with sample data.
2. **Exploring the Schema**: Refer to the database schema visualization to understand the structure of the database and relationships between different entities.
3. **Utilizing Features**: Experiment with the database features such as triggers, functions, and relationships to understand their impact on data management and integrity.
