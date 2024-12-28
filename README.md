Supply Chain Data Management & Analysis- Microsoft SQL Server

Problem Statement
The retail company faced challenges in efficiently managing its supply chain, including issues with supplier performance, stockouts, and high carrying costs. The company needed an improved system to track orders, shipments, and supplier data to optimize inventory management, reduce stockouts, and streamline the order fulfillment process.

Solution
To address these challenges, an optimized supply chain management system was implemented using SQL queries to analyze and visualize key supply chain metrics. This solution helped in identifying supplier performance, streamlining inventory management, and improving order fulfillment efficiency.

Database Schema
The database schema consisted of the following tables:

Suppliers: Stored information about suppliers (supplier_id, supplier_name, contact_person, phone_number, email).

Products: Contained details about products (product_id, product_name, description, unit_price, quantity_in_stock).

Orders: Captured order details (order_id, product_id, supplier_id, order_date, quantity_ordered, order_status).

Shipments: Stored shipment information (shipment_id, order_id, shipment_date, delivery_date, shipping_company, tracking_number).

![image](https://github.com/user-attachments/assets/301498eb-e55a-4a95-a250-71631c373440)


SQL Analysis

1) Selected all records from the Suppliers table.
2) Selected product name and unit price from the Products table.
3) Selected order IDs and order dates from the Orders table.
4) Selected shipment IDs and shipment dates from the Shipments table.
5) Counted the total number of products in stock.
6) Calculated the average unit price of products.
7) Found the maximum quantity ordered.
8) Listed suppliers along with their contact persons.
9) Listed products with their descriptions.
10) Displayed shipment details including the tracking number.
11) Listed orders along with the associated supplier information.
12) Displayed products that had a unit price greater than $15.
13) Counted the number of orders per supplier.
14) Calculated the total quantity ordered for each product.
15) Listed shipments along with the associated order information.

![image](https://github.com/user-attachments/assets/faa303d9-95dc-4e36-9698-a50636156ca2)

![image](https://github.com/user-attachments/assets/afb15cde-2a40-4aa6-9a11-14f2c15edf6b)



