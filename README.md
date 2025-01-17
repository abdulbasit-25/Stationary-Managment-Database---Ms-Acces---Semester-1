Stationery Management System 📚✏️
Overview
The Stationery Management System is a robust and user-friendly solution designed to automate and streamline operations for small-scale stationery shops. Built using Microsoft Access, it leverages relational database capabilities to efficiently manage inventory, sales, supplier interactions, and order processing. This project was developed as part of an ITC Lab assignment to enhance understanding of database design and practical applications.

Features
Inventory Management
Add, update, and categorize stationery items with real-time stock tracking.

Sales Tracking
Record sales transactions, track quantities sold, and calculate total prices.

Supplier Management
Manage supplier details, including contact information and items supplied.

Order Management
Process customer orders, track order statuses, and streamline workflows.

Report Generation
Automatically generate reports, including:

Sales reports by date range.
Low stock alerts.
Supplier contribution analysis.
Order status reports.
System Design
The system utilizes a relational database design, featuring:

Users Table: Tracks system users and their roles.
Items Table: Manages stationery item details, including categories and stock levels.
Orders Table: Stores order information and statuses.
Suppliers Table: Records supplier contributions and contact details.
Inventory Table: Tracks inventory levels and updates after sales or orders.
Entity Relationships:

Users → Orders (One-to-Many)
Orders → Order Items (One-to-Many)
Order Items → Items (Many-to-One)
Items → Inventory (One-to-Many)
Suppliers → Inventory (One-to-Many)
Key Technologies
Microsoft Access: Database creation and management.
SQL Queries: For data manipulation and report generation.
Entity Relationship Diagram (ERD): For database structure visualization.
Limitations
Focused on small-scale stationery shops.
Does not integrate with external accounting or payment systems.
Lacks e-commerce functionalities.
Future Enhancements
Integrate customer management and payment processing.
Expand scalability for medium and large-scale operations.
Develop a user-friendly interface or dashboard for better usability
