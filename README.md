# Adventure Works Data Visualization

**Objective:**

To Develop a comprehensive Power BI & Tableau dashboard that highlights key insights into sales performance, customer behavior, and product trends for the company.

**Columns:**

Fact Internet Sales Dataset contains:
Product key, Customer key, Orderdatekey, duedatakey, Shipdatekey, Sales Order Number, SalesAmount

DIM-Products Dataset contains:
Productkey, Product ItemCode, Product name, Subcategory, Product Category, Color, Size, Model Name, Product States.

DIM-Customer Dataset Contains:
Customerkey, Full Name, First Name & Last Name, Gender, Datefirst Puechere, Customer City

DIM-Date-Excel Dataset contains:
Date key, Date, Day, WeekNumba, Month, Month Shot, Month Number, Quarter, Year.

**Data Cleaning:**

1. Dropped unnecessary columns like last name and first name.
   
2. Changed the data column into date datatype.

3. Convert numerical columns into number format.

**Data Modeling:**

In Data Modeling there are 2 types.

1. Snowflake: In Snowflake, Fact table connected to normalized dimension tables, it forms more complex structure.
   
2. Star scheme: In Star Schema, Fact table surrounded by dimension tables. It is simple & easier to understand.
 
So I select Star scheme for my project.
Here My Fact Table is Fact Internet Sale dataset.

**Data Visualization:**

Created Power BI reports on analysis of customer behaviour, product trends and sales performance.

**Recommendations for Business Improvement:**

• Boost Female-Focused Marketing: Leverage slightly higher sales from female customers by creating targeted promotions.

• Maximize Peak Sales Months: Focus on June, October, and December for special offers and increased inventory to capture more sales.

• Invest in Top Products: Prioritize Road Bikes and Mountain Bikes as they drive the most sales, while reassessing underperforming accessories.

• Update Product Line: Address Outdated products by refreshing or discontinuing them to improve inventory management.

• Expand in Top Regions: Strengthen efforts in London and Paris, while growing in regions like Wollongong and Bendigo.





