In this project, used Pandas to clean a CSV dataset and export it to a SQLite database. 

Steps:
1. Import pandas and read the CSV file "academy_awards.csv" into a Dataframe.
2. Convert the "Won" column to the integer values 0 and 1 using MAP method and  "Year" column to the integer data type.<br/>
Note: SQLite uses integer values to represent Booleans.
3. Clean up "Additional Info" column (formatted as Biutiful {'Uxbal'}) </br>
to extract Movie ("Biutiful") & Character ("Uxbal")as seperate new columns.
4. After dataframe cleaning, export the dataframe to a SQLite dataframe using "to_sql" method.
5. Verify using SQL 
