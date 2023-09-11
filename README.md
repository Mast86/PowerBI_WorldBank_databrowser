# WorldBank_databrowser
A folder with CSV data and a PowerBI report to browse World Bank country data.
Read model_metadata.txt to understand how to upload new country data.

adding countries to database:
- go in the worldbank database https://data.worldbank.org/?iframe=true and browse the desired country.
- download all the indicators in CSV format.
- put the csv file into the "country_data" folder.
- add country name, file name (with .csv extension), download date to the country_file_name.xlsx table.
- refresh model.pbix file.