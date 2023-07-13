# Building Data Warehouse for a Clothing Store

In this project, I have developed a comprehensive data architecture for a clothing retail shop LEP which focuses on selling dresses. This project aims to simulate the entire process followed by data-driven companies in making decisions based on data.

The project encompasses various stages, including web scraping, data processing and transformation, database and data warehouse development, and ultimately, data analysis and decision-making. 

![lep](https://github.com/emmanguyen0602/Retail-Store-Data-Warehouse/blob/main/images/thiet-ke-shop-quan-ao-nu-lep-1.jpg)

# Project Architecture

![LEP](https://github.com/emmanguyen0602/Retail-Store-Data-Warehouse/blob/main/images/LEP%20DATA%20WAREHOUSE.drawio.png)

# Part 1: Web scraping

- Use Selenium to get product and price data from the [Lep website](https://lep.vn/).

![lep](https://github.com/emmanguyen0602/Retail-Store-Data-Warehouse/blob/main/images/Screenshot%202023-07-13%20101000.png)
# Part 2:  Generate fake data and load to central database
- Generate Random Data: employee, customer, payment.
- Design a Central RDBMS and apply normalization.
- Load the data into the central RDBMS.
# Part 3: Design data warehouse
- Create a scheme
- Generate a date dimension
- Connecting Python to MySQL
- Populate data to the tables
- Create Triggers to Automate the transfer of data: insert new customer, insert new employee, insert new transaction.

![lep](https://github.com/emmanguyen0602/Retail-Store-Data-Warehouse/blob/main/images/lep%20data%20warehouse.png)










