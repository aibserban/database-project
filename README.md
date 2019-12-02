# database-project
The following exercise consists of creating a database, designing a normalized database schema, creating tables for the schema and inserting data using **SQLite 3** and **Pandas**.

The purpose of the project is for me to gain a better understanding of database design and management.

The final database will consist of games from Major League Baseball, with data sourced from Retrosheet.org.

In this repository you will find the main datasets used:
- `game_log.csv` -> representing the primary point of concern, most columns which will end in the final database originating from here (the product of 127 separate CSV files from Retrosheet.org, more information regarding the columns in "`game_log_fields.txt`")
- `park_codes.csv` -> auxiliary file with data regarding the parks played on
- `person_codes.csv` -> auxiliary file with data regarding the relevant people and their different roles on the field
- `team_codes.csv` -> file with data containing more information on each teams that have played in the period covered

Additionaly, of course, you will find the Jupyter Notebook file as "`design_create_db.ipynb`".
