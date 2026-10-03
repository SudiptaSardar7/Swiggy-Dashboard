# Swiggy-Dashboard
1.Project Title
Swiggy Dashboard

2. Purpose
A 5-page Power BI dashboard (Overview, User Performance, City Overview, Restaurant Analysis, Insight) analysing Swiggy food-delivery sales in India, Oct 2017 to Jun 2020. It covers about ₹98.7 crore in sales, 150K orders, 148K restaurants and 100K registered users (77,929 of whom ordered).

3. Tech stack

📊 Power BI Desktop : Main Data Visualization platform used for report creation.
📂 Power Query : Data transformation and cleaning layer for reshaping and prepare for the data.
🧠 DAX(Data Analysis Expressions) : Used to calculated measures, dynamic visuals and conditional logic.
📝 Data Modeling : Relationships established among table are many-to-one. Orders -> Menu is many-to-many.
📁 File Format : .pbix for development and .png for dashboard previews

4. Data source
Data is from kaggle 

5. Features and highlights

Business problem : find which locations, customer groups and cuisines drive revenue, so marketing and offers can be targeted.
Goals: track sales, orders and users year over year. Rank top locations, profile customers, find high-value customers, and compare restaurants and cuisines.
Key visuals:
Overview: KPI cards, veg/non-veg cards, Top-N location chart, yearly trend.
User Performance: age, marital status and occupation charts, current vs previous year cards.
City Overview: sales, user and rated-restaurant bars, bubble map, detail table.
Restaurant Analysis: cuisine, type, price and rating views.

6. Insights 

Top locality: Tirupati leads (4.25 cr), then Electronic City, Bangalore (2.86 cr). The dashboard "city" field is actually a locality, so Delhi and Bangalore are each larger once grouped by city.
Growth: sales rose about 343% in 2018 (overstated, since 2017 covers) and fell about 19% in 2019. 2020 covers only Jan to 26 Jun.
Customers: ages 21–25 are the largest group. Students bring in 53% of revenue and men about 57%, which supports targeted campaigns and offers for female customers.
Top customers: the top 10% generate about 69% of sales, which supports a VIP program.
Veg vs non-veg: close to balanced. Non-veg items cost more on average. This covers only restaurants with menu data, about 12.5% of sales.

7. Screenshots
   Overview:https://github.com/SudiptaSardar7/Swiggy-Dashboard/blob/main/Overview.png
   User_Performance:https://github.com/SudiptaSardar7/Swiggy-Dashboard/blob/main/User_Performance.png
   City_Overview: https://github.com/SudiptaSardar7/Swiggy-Dashboard/blob/main/City_Overview.png
   Resturant_Analysis:
   Insight: https://github.com/SudiptaSardar7/Swiggy-Dashboard/blob/main/Insight.png 
   
