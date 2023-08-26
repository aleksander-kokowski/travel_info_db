This is my first GitHub project in SQL language. I created PostgreSQL database called 'travel_info'. 
It's main purpose is to help people travelling from my country - Poland. It stores data in 7 tables called:
1. country - stores data about countries in the world with 18 columns of basic information that is essential for every traveller
2. currency - stores data about world's currencies essential for traveller including availability on popular financial technology app 'Revolut'
3. language - stores data about world's languages including used writing system
4. religion - stores data about world's religions including link to Wikiedia page
5. entry_conditions - stores data about a documents needed for travel e.g. ID cars, passport
6. driving_licence - stores data about driving licence types essential to know for a traveller
7. vaccines - stores data about vaccines that are mandatory to have in order to travel to some countries

I filled database with data about 20 countries useful to test some queries but it can be filled with more records.

The repository contains:
creating_database.txt - file with code used to create database
database_queries.txt - file with code used to insert records to tables and create views containing some basic queries used on data
backup_db.backup - database backup file
export_to_csv.txt - file with code used to export database tables to 7 .csv files
7 .csv files containing data from 7 tables
travel_info_schema.png - schema created in erd.dbdesigner

Dictionary of some words and abbreviation used in database:
eu - European Union
dowód osobisty - ID card
paszport - passport
wiza - visa
podstawowe - basic
chrześcijaństwo - Christianity
międzynarodowe - international
