# 📊 MiniBiz Data System

**MiniBiz Data System** is a lightweight and scalable database model designed for small businesses.  
It helps manage **inventory, orders, customers, employees, sales, and purchases** in one unified system.  

---

## 🚀 Features
- 🛒 Manage customers, orders, and sales  
- 📦 Track raw materials and finished goods inventory  
- 📑 Record purchases and supplier details  
- 👨‍💼 Store employee data with roles and salaries  
- 📈 Run queries to generate business insights and reports  

---

## 📌 Project Stages

- [x] **Stage 1 – Database Design**  
  - Define entities (Inventory, Orders, Customers, Employees, etc.)  
  - Create ER Diagram  
  - Write SQL schema for all tables
  - create indexes and set table relationships  

- [x] **Stage 2 – Data Insertion & Sample Records**  
  - Insert test data (customers, orders, products)  
  - Populate inventory and sales records  

- [ ] **Stage 3 – Queries & Reports**  
  - Write SQL queries for sales reports, stock levels, and customer purchases  
  - Create summary views (monthly sales, inventory usage, etc.)  

- [ ] **Stage 4 – Optimization & Constraints**  
  - Add primary/foreign keys, indexes, and constraints  
  - Ensure data consistency and referential integrity  

- [ ] **Stage 5 – Future Enhancements**  
  - Build a simple UI or API on top of the database  
  - Add role-based access (admin, staff, manager)  
  - Export reports (CSV, Excel, PDF)  

---

## 🏗️ Database Schema
The system consists of the following core tables:  
- **Customers** – Customer details  
- **Orders & OrderDetails** – Orders with multiple products  
- **Inventory** – Raw materials and finished goods  
- **Employees** – Staff details and roles  
- **Suppliers & Purchases** – Supplier records and purchase transactions  
- **Sales** – Records of completed sales  

*(ER Diagram to be added here)*  

---

## ⚙️ Setup Instructions

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/minibiz-data-system.git
   cd minibiz-data-system
