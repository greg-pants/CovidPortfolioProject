1. Sourced my data from https://ourworldindata.org/covid-deaths

2. Cleaned data in excel file to create Covid Deaths dataset
  - Cut population column and inserted it next to date column (column D).
  - In this file i kept total_deaths, new_deaths, total_cases, new_cases, population, date, location
  - made sure to save this as one file then undid all these changes to create a separate dataset file

3. Created Covid Vaccination file
  - got rid of columns in covid deaths file
  - focused on vaccination data and demographics of vaccination cases

4. Utilized SQL Import and Export Wizard tool to import both datasets into my native client SQL server
   - Made sure to create a new database in my server to become this import process and queries

5. Began my check queries in the Covid Portfolio Project file to ascertain numbers

6. After numerous queries i joined both tables by date and location
   - idea was to look at total population compared to number of vaccinations (i had population in my coviddeaths file so this was my rationale)

7. Utilized CTE before creating a temporary table
   - used cte to create a proper Rolling count of people vaccinated
   - in this i also joined the location and dates of each dataset to equal each other to avoid data quality issues

8. Created a view to store data for later visualizations

-----------------------------------------------------------------------------------------------------------------------------------------------------

Tableau Portion of Project

1. Condense queries from previous files into a single query file

2. Saved each query as an individual excel file (couldnt import an sql file with tableau public, only excel files)

3. Created a sheet for each file

4. Created a visualization dashboard that combines the metrics of each file.

5. can find my visualization here: https://public.tableau.com/app/profile/gregory.pantaleone/viz/CovidPortfolioProject_16914344657220/Dashboard1



