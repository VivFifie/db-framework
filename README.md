# db-framework

■ A brief explanation of your approach.

The tables created have broken doen the data into its most granular formart. We have 3 tables i.e 
tbl_company - This is the table that hold our clients. This hold information about their name,location and industry they operate in.We are going to generate a unique id for each company we add onto this table.

tbl_customers - This hold the details of the customers from the data shared by the different companies. The company id is a foreign key on this table.

tbl_transactions - This table holds all transactions shared from the differnt companies for the different customers. The company id is a foreign key onto this table, same as the customer id. A customer could have many transactions form the many differnt companies.


■ Instructions for running the SQL scripts.

The scripts have been organised into different directories i.e 

/schmea contains the sql scripts used to create the database,tables and indexes. The scripts have been organised sequencially therefor they should be easy to run through.

/view contains the sql script to create the tbl_transactions view.

/partitioning_sharding_strategy contains the approach used to ensure tbl_transactions table is capable for handling billions of data from the diffrent companies. 


■ Any assumptions or additional considerations.

The assumption is:

We will have enough resources to hold our databases either on premise or on could.

Postgres has been optimized efficiently in consideration of the infrastruture resoucres availed.

