# SuperStoreInteractiveDashboard-UsingPowerBI
Analyzing superstore dataset and finding key insights

Objective: To build an interactive dashboard using PowerBi desktop application and finding key insights from the dataset

About the dataset:
This [data](https://github.com/karthikdoijode/SuperStoreInteractiveDashboard-UsingPowerBI/blob/main/global_superstore_2016.xlsx) we downloaded form Google and it has 3 tables such as Orders, People and returns. This data is about details of various products of different categories such as furniture,office supplies and technology where each category has many sub-category products. In orders table we have information like Order date, Ship date, Customer name, region, country, sales and many more. In returns table we have information such as which order is returned from which region. And in people table we have name of the person and their region.

Tasks perfomed on this data:
- 1.Connecting to database: first we imported this excel data to PowerBi desktop
- 2.Analyzing tables and relations: We analyzed data and relationship between the tables also analyzed relationship between the columns in each table
- 3.Data cleaning: This is an important step where we keep only significant data by removing unwanted data using power query editor and few formulas using dax. We structured data in people and returns table where we didn't have column name for the features and we introduced few new columns based on the information already present, like we found out average delivery day from shipping and order date. We removed rows having 0 delivery days which means orders which are delivered on the same day.
- 4.Developing model: We inter-related tables using suitable columns from each table
- 5.Creating dashboard: This is the final interactive dashboard we got after performing the above tasks.


Conclusions:
- Built an interactive dashoard with key insights such as top 5 profitable products, top 5 products which are making a loss, top 10 customers who are contributing to maximum profit and introduced slicer for each individual year to make it more interactive
- Reported sales on each segment and on each market type
