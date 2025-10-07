# G3_EDD_SUPP
Data Warehousing course deliverables – Group 3 (William BELLON &amp; Guillaume REAULT) for the M1 Big Data &amp; AI program
This repository contains both the database in SQL format and the executive summary in DOCX format.

## Database:

The database has been constantly evolving throughout this course. It is intended to include our four datasets originally provided as CSV files at the start of the course. These four tables were modified to be compatible with MariaDB, notably by defining primary keys, foreign keys, appropriate data types, and auto-increment settings where necessary.
They were then linked together within the database, and a “date” table was added to keep track of the insertion dates of newly added data.
The next objective was to create a fact table from the existing tables. This fact table contains all the order records along with all associated details, particularly regarding customers and products.
Once this was completed, several views were created to retrieve the data needed for different KPIs. Finally, user permissions were added, and data anonymization was performed.

## Executive Summary:

The executive summary includes the context of the project, followed by the different indicators that were created, along with their descriptions and interpretations.
