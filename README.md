# MySQL Structure – Pizzeria

## 📌 Description  
This project consists of the design of a relational database for an online food ordering system.  
The work focused on structuring entities and relationships to manage customers, orders, products, stores, employees, and deliveries.

The database uses **Primary Keys (PK)** and **Foreign Keys (FK)** to ensure referential integrity and proper data organization.

Different types of relationships were implemented:

- One-to-many (Customer → Orders, Store → Orders, Store → Employees)
- Many-to-many (Orders ↔ Products, using an intermediate table)
- One-to-one (Order → Delivery)

Additional design decisions include the use of **ENUM types** and optional fields (e.g. category for pizzas) to adapt the model to real scenarios.


## 🛠 Technologies  
- MySQL  
- MySQL Workbench
- XAMPP
- MAMP

## 📂 Project Structure
- `pizzaStoreGraphicSchema.png` >> Database model schema
- `pizzaStoreScript.sql` >> SQL script  
- `README.md` >> Documentation  

## 📸 Demo  
Open the `.png` file in MySQL Workbench to visualize the schema.

## 🚀 Installation  
1. Clone the repository  
   git clone https://github.com/your-username/mysql-estructura-pizzeria.git

## 📚 References
- MySQL Workbench Official Site  
  https://www.mysql.com/products/workbench/  

- MySQL Documentation  
  https://dev.mysql.com/doc/mysql-apt-repo-quick-guide/en/  

- ER Diagram Tutorial (Guru99)  
  https://www.guru99.com/er-diagram-tutorial-dbms.html  

- YouTube Tutorials  
  https://www.youtube.com/watch?v=7S_tz1z_5bA  
  https://www.youtube.com/watch?v=w-0IWyAeZ3M  

- MySQL Data Types Guide  
  https://disenowebakus.net/tipos-de-datos-mysql.php     


