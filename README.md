#  Food Plaza – Online Food Ordering System

##  Project Overview

Food Plaza is a simple and user-friendly web-based food ordering system developed to make online food ordering easy for customers and efficient for administrators. Customers can browse food items, add them to their cart, place orders, and manage their profiles, while administrators can manage food items, monitor orders, and update order statuses. The system is designed with role-based access to ensure security and smooth operation.



##  Objectives

* **Simplify Food Ordering**: Enable customers to browse menus and place orders without hassle.
* **Efficient Admin Management**: Help administrators easily manage food inventory and customer orders.
* **Role-Based Access Control**: Provide secure access with separate functionalities for admins and customers.
* **Profile Management**: Allow users to view and update their personal information.
* **Real-Time Order Updates**: Keep customers informed about their order status.
* **User-Friendly Interface**: Ensure easy navigation with a clean and responsive design.


##  Technologies & Tools Used

* **JSP (JavaServer Pages)** – Used to create dynamic and interactive web pages.
* **Eclipse IDE** – Development environment used for coding and debugging.
* **MySQL Connector** – Connects the Java application with the MySQL database.
* **MySQL Database** – Stores user details, food items, cart data, and orders.
* **XAMPP Server** – Used to host the application and manage the database locally.



##  Database Tables

### 1. `fooditem`

* Stores details of available food items such as Food ID, name, price, and category
* Allows admins to add, update, or delete food items

### 2. `customer`

* Stores customer details like name, email, and contact number
* Helps manage customer profiles and order history

### 3. `signup`

* Manages user registration and login
* Stores username, email, password, and user role (admin or customer)

### 4. `cart`

* Stores food items selected by customers
* Used for order placement and tracking



##  Methodology

### 1. Requirement Analysis

* Identified essential features such as user registration, login, food management, cart handling, and order tracking
* Clearly defined roles and responsibilities for admins and customers

### 2. Design Phase

* Designed a modular structure using JSP for better maintainability
* Created a well-structured MySQL database schema

### 3. Implementation

* Developed the application using Eclipse IDE
* Integrated JSP with MySQL using MySQL Connector
* Created separate dashboards for admin and customer users

### 4. Testing & Deployment

* Tested all major functionalities including food operations, cart management, and order updates
* Deployed the project locally using XAMPP

### 5. Iterative Enhancements

* Improved features based on testing and feedback
* Designed the system to support future upgrades



##  Key Features

* Secure login and logout functionality
* Separate dashboards for admin and customer users
* Dynamic food menu management
* Cart and order tracking system
* Real-time order status updates
* Simple and responsive user interface



##  Future Enhancements

* Integration of online payment options
* Improved mobile responsiveness
* Order history and invoice generation
* Notification system for order confirmations and updates




