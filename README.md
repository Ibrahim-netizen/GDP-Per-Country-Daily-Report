## GDP-Per-Country-Daily-Report

This project was aimed at scheduling a daily dashboard report of Gross Domestic Product Per Country at a specific time to:
- Visualize the GDP per capita values over time to trends in countries' economic growth.
- Demonstrate GDP per value by country on the map
- Identify countries with the highest and lowest GDP per capita value.
- Compare GDP per Capita values across countries.
- Study income disparities between countries.

Another is to demonstrate enterprise-scale analytics data architecture which involves importing data into a database system or data warehouse then query and transform the data before importing it into a data visualization tool to display charts of desired metrics.

#### The Deliverables include 
- GDP Per Country Database
- An SQL function, View, and stored procedure in PostgreSQL
- Scheduled job with PostgreSQL PgAgent
- GDP Per Country daily Dashboard report in Power Bi

#### Data
The data was sourced from https://github.com/Pitsillides91/Power-BI-raw-data/blob/master/SQL%20to%20Power%20BI/gdp_raw_data.csv It comprises the gross domestic product per capita value per country and the year for recorded value from 1970 to 2017 as well as the location code and flag code of each country.


![image](https://github.com/Ibrahim-netizen/GDP-Per-Country-Daily-Report/assets/76513466/32b67299-cf13-4329-82f3-9d5c486d9149)



To achieve the deliverables, I automated the creation of a daily dashboard report of countries' GDP per capita by connecting PostgreSQL with Power Bi where I used SQL to create a relational table and imported the CSV file into PostgreSQL, and designed a view to filter out my desired attributes then created a stored procedure to import daily GDP Per country data automated with PgAgent scheduled to run at 7am daily except weekends. Then I connected it to Power Bi using the import method and designed my dashboard to show trends of GDP Value by Country, and Year with list values and button sliders to show economy performance and inflation.



![image](https://github.com/Ibrahim-netizen/GDP-Per-Country-Daily-Report/assets/76513466/328ad10a-9836-4957-9e9a-815e1603369c)



Aside from the aforementioned deliverables, the daily automated dashboard can be used to advise policymakers, economists, and business stakeholders to analyze the impact of economic factors such as population and gross domestic product for countries per year on designing monetary and fiscal policy, economic shocks, and tax and spending plans.

#### Results and Observations

Below are the results and observations drawn from the created dashboard report of all the countries around the world from 1970 to 2017.

As of 2017, the United States of America (USA) has the highest Gross domestic product value of up to $19.5 Trillion whilst Luxembourg has the highest GDP per capita value of $104,498.74 compared to others. This can be attributed to the USA's large affluent population and robust business environment as well as her natural resources and history of innovation. Luxembourg's high GDP per capita value also has a strong economy with an established presence as a global financial center although with less population. Thanks to her favorable tax policies and highly skilled workforce, the citizens of Luxembourg live very well above the poverty line.

On the other hand, Somalia has the lowest sum of GDP value and GDP per capita value of around $33.5B and $2,408.50 respectively followed by Eritrea and South Sudan. Both Somalia and Eritrea experienced significant political instability causing inadequate basic amenities available to their citizens as well as limited natural resources and economic sanctions are major reasons why they have the lowest GDP values in the world as of 2017.

Furthermore, the observed values for each country can be used to identify their income disparities as well as identify countries with low standards of living.















