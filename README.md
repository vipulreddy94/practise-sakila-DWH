# Data Modeling of a DW based on star schema. 
### An existing relational DB is converted to DWH. 

- This project is to model and develop a data warehouse for Sakila DB, based on the ***star schema***. <br/> 
- Python is used for the purpose of this project, specifically **iPython-sql** is used to create tables, and insert data into the tables. <br/>
- There is **one fact table** in the DWH, which contains the factual data and **four dimension tables**, which contain all other attributes in the relational database. <br/> 
- Data warehouse is not known for its data redundancy, instead it aims to provide a **faster processing time** for running ad-hoc queries, 
which is made possible through replicating information in multiple tables, by way of **lesser number of joins** needed for running ad-hoc queries. 
