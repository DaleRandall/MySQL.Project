# MySQL Project

The data used in MySQL included a variety of datasets, ranging from customer information to sales and inventory data. Different queries were used to extract relevant information from the datasets, enabling analysis of the data and generation of insights to inform decision-making.

Some of the queries used included:

SELECT: Used to extract specific columns of data from tables
JOIN: Used to combine multiple tables by matching values in common columns
GROUP BY: Used to group rows of data based on specific criteria
WHERE: Used to filter data based on specific conditions
ORDER BY: Used to sort data in ascending or descending order based on specific columns
Using these queries, relevant data was extracted from the datasets, allowing for analysis of various metrics, such as customer demographics, sales performance, and inventory levels. The insights generated from the analysis can be used to inform strategic decision-making, improve operational efficiency, and optimize sales performance.

Overall, the use of different queries in MySQL enabled the extraction of relevant data from large and complex datasets, facilitating data analysis and generation of insights to inform business decision-making.

USE sql_store;
Select *
From customers

![Picture1](https://user-images.githubusercontent.com/126267763/232031819-10d46a95-bd74-4ae1-ba48-460ce52d1abd.png)

SELECTT last_name, first_name, points, (points + 10) * 100 as discount_factor 
FROM CUSTOMERS;
![Tast1](https://user-images.githubusercontent.com/126267763/232031908-ad58206a-cce7-4087-8f10-5ca6f45c3310.png)

USE sql_inventory;
Select * From products
ORDER BY quantity_in_stock desc
LIMIT 1;

![Task4](https://user-images.githubusercontent.com/126267763/232032005-256f6ec0-270b-4b38-863d-efbebf7e0ec9.png)

### EER Diagram

![EER](https://user-images.githubusercontent.com/126267763/232032105-143ec1a9-676d-4936-8806-46bb7c9a2fbf.png)
