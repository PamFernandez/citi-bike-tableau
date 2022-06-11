18 Tableau – Citi Bike Analytics

Downloaded 12 zipped .csv files from the Citi Bike website

Put all 12 files into one file into one file

Normalized the data
- Formatted the date and time
- Calculated the trip duration (in seconds)
- Did a vlookup to change the old station id numbers to the new station identifiers
- Changed old member types to match the new types (subscriber became “member”, and customer became “casual”)

The file "2021CitiBikeData_Consol.csv" was too big to upload to GitHub. So I pivoted and did just one season of information - Summer 2021.

Data Cleaning File: data_cleaning.ipynb
Tableau Link: https://public.tableau.com/app/profile/pam.fernandez/viz/Summer2021CitiBikeAnalysis/Story1
