"""
WORLD BANK data browser
author: Matteo V. Rocco

description:
Power BI data browser for World Bank country data

user notes:

1. DATA MANAGEMENT 
All country data are stored in the /country_data folder.
Data can be taken and updated from https://data.worldbank.org/ .
If a country must be added, download all its indicators from the website in CSV format and add the file in the data folder (rename it with the region acronym).
Then add the country in the Power BI dataset and refresh it.
In Power BI report, set appropriately the database_path variable to access the local data

