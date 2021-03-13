# etl_project

Group: business_up_top
Proposal: ETL on Order Sales Data and Dow Jones Industrial Average
Transformation Type: (see below) Data Base Type: Relational Why This: Impact of the stock market on sales orders

Extract: your original data sources and how the data was formatted (CSV, JSON, pgAdmin 4, etc). 
Data Source: Kaggle (but 2 different sources) 
Data Format: .CSV

Transform: what data cleaning or transformation was required.
1. Convert dates in excel to a consistent format
2. Read in both CSV files into JN separately
3. Convert all date(s) in both files to Pandas DateTime for consistentcy
4. Change column names to lower case and underscored for SQL to read in
5. Select only the columns needed
6. Set up schema in pgAdmin
7. Jin tables on [TBD]

Load: the final database, tables/collections, and why this was chosen.
