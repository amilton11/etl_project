# etl_project

Group: business_up_top\n
Proposal: ETL on Order Sales Data and Dow Jones Industrial Average\n
Transformation Type: (see below)\n 
Data Base Type: Relational\n 


Extract:\n 
Data Source: Both files came from separate sources on Kaggle\n
Data Format: .csv\n

Transform:\n
1. Convert dates in excel to a consistent format\n
2. Read in both CSV files into JN separately\n
3. Convert all date(s) in both files to Pandas DateTime for consistentcy\n
4. Change column names to lower case and underscored for SQL to read in\n
5. Select only the columns needed\n
6. Set up schema in pgAdmin\n
7. Jin tables on [TBD]\n

Load: the final database, tables/collections, and why this was chosen.
Final DB: [TBD]\n
Tables: [TBD]\n
Why: The purpose of this DB is compare daily sales aginst stock\n
