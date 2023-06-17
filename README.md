## GDP-Per-Country-Daily-Report
This project was aimed at scheduling a daily dashboard report of Gross Domesic Product Per Country at a specific time. 
Another is to demonstrate enterprise-scale analytics data architecture which involves importing data into database system or data warehouse then query and transform the data before importing into a data visualization tool to display charts of desired metrics.

#### The Deliverables include 
- GDP Per Country Database with PostgreSQL
- An SQL function and stored procedure in PostgreSQL
- Scheduled job with PostgreSQL PgAgent
- GDP Per Country daily Dashboard report with Power Bi

##### Data
The data was sourced from https://github.com/Pitsillides91/Power-BI-raw-data/blob/master/SQL%20to%20Power%20BI/gdp_raw_data.csv

![image](https://github.com/Ibrahim-netizen/GDP-Per-Country-Daily-Report/assets/76513466/32b67299-cf13-4329-82f3-9d5c486d9149)


It comprises of the gross domestic product per capita value per country and the year for recorded value from 1970 to 2017 as well as the location code and flag code of each country.

To achieve the deliverables, I automated the creation of daily dashboard report of countries' gdp per capita by connecting PostgreSQL with Power Bi where I used SQL to create a relational table and imported the CSV file into PostgreSQL and desinged a view to filter out my desired attributes then created a stored procedure to import daily GDP Per country data automated with PgAgent scheduled to run at 7am daily except weekends. Then I connected it to Power Bi using the import method and designed my dashboard to show trends of GDP Value by Country, and Year with list values and button sliders to show economy performance and inflation.



![image](https://github.com/Ibrahim-netizen/GDP-Per-Country-Daily-Report/assets/76513466/328ad10a-9836-4957-9e9a-815e1603369c)



Aside the aforementioned deliverables, the daily automated dashboard can be used to advise policymakers, economists and business stakeholders to analyze the impact of economy factors such as population and gross domestic product for countries per year on designing monetary and fiscal policy, economic shocks and tax and spending plans.

