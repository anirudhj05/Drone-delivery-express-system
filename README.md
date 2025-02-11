# Drone Dispatch! Express Delivery Database System
# Overview
This project is a database system intended to monitor and manage deliveries of grocery products via drones for a third-party grocery service. The system supports user interactions from order placement to delivery, including price comparisons and electronic payments to stores.

# Project Scenario
This database is designed to handle the delivery logistics for a third-party grocery service that connects customers with multiple grocery stores. Customers can place orders through the service, which finds the required products at optimal prices and arranges for drone delivery. Upon successful delivery, payment is processed electronically from the customer to the store.

# Methodology
The project started with creating an enhanced entity-relationship diagram (EERD) by mapping out entities like users, stores, orders, products, and drone. Following the mapping, relationships between the different entities were defined (one-to-many, many-to-many, etc) which was necessary for operational logistics. Detailed attributes for each entity with primary keys were identified for relational integrity.

![image](https://github.com/user-attachments/assets/b255e04b-ff29-44be-be13-efcb52f014af)

This EERD was translated into a relational schema, structuring the different entities into relational tables. This step involved writing SQL scripts that not only create these tables but also define the column types, primary keys, foreign keys, and enforce constraints. These measures are critical because they ensure the database's integrity and operation within the established relational dynamics. This systematic method helps to prevent data anomalies and improves the database's scalability and performance.

The final step involved develop stored procedures and functions to improve operational efficiency and maintain data consistency.
- User Authentication: This procedure ensures that user access is secure by verifying credentials, a fundamental aspect of maintaining the integrity of user data.
- Transaction Handling: This manages the logistics of order processing and e-payments, which is important for ensuring that transactions are processed reliably and funds are appropriately allocated.
- Multi-User Management: Coordinates simultaneous access by multiple users, maintaining consistency and preventing conflicts, which is necessary in a multi-user environment where transaction timing is very important.
- Data Retrieval Functions: These are designed to simplify certain activities such as calculating totals or checking limitations, which are critical for adhering to business regulations and increasing data operational efficiency.

This drone delivery database improved query performance by 20%, improving the responsiveness and efficiency of the database. This project marks an important step in applying database design concepts to real-world business requirements, combining strong academic knowledge with practical implementation skills.

