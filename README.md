#  Online Food Ordering System – Food Plaza

### Screenshots
Screenshots demonstrating the working of the system are included in the uploaded project report.

---

## About the Project
Food Plaza is an online food ordering system designed to make ordering food easier for customers and management simpler for administrators. Customers can browse food items, add them to a cart, and place orders online, while admins can manage food inventory, update order statuses, and monitor all orders. The system provides a smooth, role-based experience with secure login and a user-friendly interface.

---

## Project Overview
The system is built using JSP for dynamic web pages and MySQL for database management. Customers and admins have separate logins, ensuring role-based access. Customers can view menus, manage their cart, and track orders, while admins can add, update, or delete food items and update order statuses. The architecture focuses on simplicity, efficiency, and real-time updates.

---

## How the Project Works
- **User Signup & Login**: Users register and log in securely. Admins and customers have separate logins.  
- **Food Browsing**: Customers browse available food items categorized by type and price.  
- **Cart Management**: Customers can add items to their cart and place orders.  
- **Order Processing**: Admins view new orders, update their status (e.g., preparing, delivered), and manage the food inventory.  
- **Profile Management**: Both customers and admins can view and update their profile details.  
- **Real-Time Updates**: Customers can track order status as updated by the admin in real time.  

This workflow ensures that customers can place orders efficiently while admins can manage the system smoothly.

---

## Database Tables
The system uses the following MySQL tables to manage data efficiently:

| Table Name | Purpose |
|------------|---------|
| **fooditem** | Stores food item details such as Food ID, Name, Price, and Category. Admins can add, update, or delete food items. |
| **customer** | Stores customer details like Name, Email, and Contact. Used for managing profiles and order history. |
| **signup** | Handles user registration and login, storing Username, Email, Password, and Role (Admin/Customer). |
| **cart** | Stores items added to the customer’s cart and manages order placement and tracking. |

These tables help organize data and enable smooth interaction between the frontend and backend.

---

## Key Features
- Secure signup and login for customers and admins  
- Role-based dashboards  
- Dynamic food menu management by admin  
- Cart functionality and order tracking  
- Real-time order status updates  
- Simple and responsive user interface  

---

## Tools & Technologies Used
- **JSP (JavaServer Pages)** for building dynamic web pages  
- **Java** for backend logic  
- **MySQL** for database management  
- **MySQL Connector** for Java–database integration  
- **Eclipse IDE** for development and debugging  
- **XAMPP Server** for local hosting and database management  

---

## Project Goals
- Simplify online food ordering for customers  
- Enable admins to efficiently manage food items and orders  
- Provide secure role-based access  
- Offer real-time updates for transparency  
- Deliver a user-friendly interface  

---

## Applications
- Online food ordering platforms for restaurants  
- Efficient inventory and order management for admins  
- Customer-friendly systems for fast and accurate food delivery  
- Basis for future enhancements like online payments and mobile-friendly design  

---

## Conclusion
Food Plaza demonstrates how web technologies like JSP and MySQL can be combined to build a practical online food ordering system. The project successfully separates customer and admin roles, supports real-time order tracking, and provides an efficient, user-friendly experience. It serves as a strong example of applying technology to improve everyday services.
