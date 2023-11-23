# Financial Portal Database "Finam"

This repository contains a database created based on data from the financial portal "Finam." Here is a general description of the database, its structure, scripts for creation and data population, as well as examples of typical queries and the usage of views, stored procedures, and triggers.

## Database Description

The "Finam" database is designed to store information about financial instruments, quotes, news, user transactions, and other related data. The main tasks of the database include tracking financial instruments, providing up-to-date quotes, analyzing technical indicators, as well as recording user transactions and interests.

## Database Structure

The database includes the following main tables:

1. **Table: type_instruments**
    - Type of instrument, such as stocks, bonds, gold, etc.

2. **Table: instruments**
    - Financial instrument containing information about the instrument itself, its description, and affiliation to a specific market.

3. **Table: stocks**
    - Information about the quotes of financial instruments, including opening, closing, high, and low prices, trading volume, etc.

4. **Table: technical_analyzes**
    - Results of technical analysis, including indicators, periods, and recommendations.

5. **Table: indicators**
    - List of indicators for technical analysis.

6. **Table: periods**
    - List of periods used in technical analysis.

7. **Table: recommendations**
    - Statuses of recommendations for technical analysis.

8. **Table: calendar_events**
    - Calendar of events, including event descriptions and comments.

9. **Table: news**
    - News related to instruments, including news descriptions, status, author, and source.

10. **Table: users**
    - User information, including email and phone.

## ERDiagram

![ERDiagram](path/to/your/diagram.png)

## Scripts

- **create_tables.sql**: Contains scripts to create the structure of the database with primary keys, indexes, and foreign keys.
- **populate_data.sql**: Contains scripts to populate the database with test data.
- **sample_queries.sql**: Includes typical queries, groupings, JOINs, and nested tables.
- **views.sql**: Contains scripts to create views in the database.
- **stored_procedures_triggers.sql**: Includes scripts to create stored procedures and triggers.

## Usage

1. **Create Tables**: Run `create_tables.sql` to create the structure of the database.

2. **Populate with Data**: Run `populate_data.sql` to add test data to the database.

3. **Typical Queries**: Use `sample_queries.sql` to perform typical queries.

4. **Views, Procedures, and Triggers**: Utilize `views.sql`, `stored_procedures_triggers.sql` to create views, stored procedures, and triggers, respectively.

