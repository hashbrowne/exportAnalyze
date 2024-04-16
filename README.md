# exportAnalyze
export spotify library to csv

-register an app via the spotify api to obtain client id, client secret, and redirect uri
-fill out the blank client_id, client_secret, and redirect_uri variables in main.py
-on line 67 of main.py, add a name for the excel file to be written to: .ExcelWriter('filename.xslx') 
-install required libraries
-python3 main.py -> authorize account when redirected

-save file off as a csv prior to running any of the analysis scripts
-make sure to add the name of the csv into any of the analysis scripts you run

=the csv example has several columns that were produced via transformations in Excel (added_at -> year_added & month added, release_date -> release_year, duration (ms) -> duration (s))
