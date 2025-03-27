Bike-Store-Portfolio-Project

A data analytics project using dummy data(SQL, Excel, Tableau)
# Bike Store

![Image](https://github.com/user-attachments/assets/6ed911e3-fe3f-4eec-9ebe-e0c39afd89d9)
![Image](https://github.com/user-attachments/assets/7fd127e9-0a8e-41cf-a729-dd74985ffe9e)

### Tableau dashboard link:
https://public.tableau.com/app/profile/collin.christopher.see/viz/BikeStorePortfolioProject_17423921980730/Dashboard1?publish=yes

## Content

- Problem Statement
- Steps followed
- Insights & Possible Follow-up Actions
- Summary

## Problem Statement

Identify condition of the sales activities and gain insights/trends happening over sales volumes
over the 2016 to 2018 period. 

Identify revenues per region/store/product category/brand and list of top customers/sales reps.

### Steps to complete
1. Collect and gather the data
2. Clean the data
3. Visualize and analyze the data(I used Excel and Tableau to create 2 dashboards for this portfolio)
4. Interpret the results

### Steps followed 

- Step 1 : Load SQL server sample database, Identify what features are necessary from the dataset and write a SQL code to collect the data. (Order ID, Customers first and last name, city, state, order date, sales volume, revenue, product name, product cat, brand name, store name, sales rep)

- Step 2 : Write SQL query to preprocess the data, create new columns such as revenue and total units.

![Image](https://github.com/user-attachments/assets/d4ce78cf-5cac-4f4d-bc21-7d8a5a5fdc5e)

- Step 3 : Connect queried dataset to Excel.

<img width="956" alt="Image" src="https://github.com/user-attachments/assets/c569ddd8-f543-478f-9bfe-90043dac4fe7" />

- Step 4 : Check column quality & clean data(drop duplicates, format data, etc)

<img width="960" alt="Image" src="https://github.com/user-attachments/assets/9dbcf2f4-753f-45f9-9af4-d518aa30621f" />

### Excel Dashboard Creation

- Step 5 : Create pivot tables to prepare data for visualization.

<img width="714" alt="Image" src="https://github.com/user-attachments/assets/3440cd8b-08bd-41ff-a2e2-ae04800f96bb" />

- Step 6 : Pick and test visualizations for our dashboard to consider what can provide the most value to our users. 

<img width="720" alt="Image" src="https://github.com/user-attachments/assets/421f4d1f-a039-445b-9257-59e4a45f75e8" />
<img width="805" alt="Image" src="https://github.com/user-attachments/assets/cc2c570c-beb4-4b43-854a-4bb3b336b12f" />

(In this regard, we have chosen charts to display revenue by year, revenue over months, revenue by state, revenue by store, revenue by category, top 10 customers, and top sales reps)

### Tableau Dashboard Creation

- Step 7 : Loaded the Excel dataset connected from the SQL queried database.

- Step 8 : Created similiar charts to the Excel with more visual formatting.
(Dashboard link: https://public.tableau.com/app/profile/collin.christopher.see/viz/BikeStorePortfolioProject_17423921980730/Dashboard1?publish=yes)

![Image](https://github.com/user-attachments/assets/6ed911e3-fe3f-4eec-9ebe-e0c39afd89d9)
![Image](https://github.com/user-attachments/assets/7fd127e9-0a8e-41cf-a729-dd74985ffe9e)


# Insights & Possible Follow-Up Actions

- 2018 had a significant drop in sales after April, resulting in the least profitable year so far, further analysis is required to find out the reason for such a drastic reduction in sales(for example, failed marketing campaigns, loss of certain sales reps, etc)

![Image](https://github.com/user-attachments/assets/f467200a-a56e-4b93-9dd6-af99379b5c15)

- Baldwin Bikes is consistently the highest in sales each year, we may want to do a further comparison of how they run differently from the other stores to see if any strategies can be implemented to help the profitability of other stores. 

![Image](https://github.com/user-attachments/assets/51766535-0271-445e-ae96-ff0d62a0e9ec)

- Mountain bikes have most of the share of sales and electric bikes are the least, depending on what direction the business decides, we can either provide a stronger marketing strategy for electric bikes or continue focusing on mountain bikes.

![Image](https://github.com/user-attachments/assets/e6fb2b27-abc3-453b-9131-de7ca5b25f6a)

- New York has the highest sales for bikes, we can do further analysis to find out why. Whether it's a specific demographic in New York that is more present so we can do targeted marketing in other regions, or it's just New York is more bike friendly so can decide on other strategies moving forward.

![Image](https://github.com/user-attachments/assets/83063d08-d8d2-463b-ae23-0af542cf34b7)

- By identifying the top customers, we can do an analysis of the demographics of top bike purchasers to create targeted marketing strategies and conduct targeted surveys to find out why they are willing to spend more on bikes.

![Image](https://github.com/user-attachments/assets/92175232-67a4-4c1d-a515-bcb19e45ea92)

- Marcelene Boyer & Venita Daniel are the top 2 leading sales reps by a significant margin, so the company should provide incentives for them to stay and share their sales strategies to the rest of the team.

![Image](https://github.com/user-attachments/assets/79ce727c-143f-475a-8d05-0b6851caeeba)

# Summary

- From the insights above, it can be shown how the dashboard can be used to find further insights for the users/business, and depending on which direction to stakeholders decide to go, we can use the relationships between the data to do further analysis to suggest the best courses of action and form business strategies.
