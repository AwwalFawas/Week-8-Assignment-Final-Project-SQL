### 📘 **Project Overview**

This project is a complete **Relational Database Management System (RDBMS)** for an **E-commerce Store**, designed and implemented using **MySQL**.
It manages customers, products, orders, suppliers, and payments efficiently while enforcing **data integrity** through relational constraints.

---

### 🎯 **Objectives**

* Design a **normalized relational database schema**.
* Apply proper **constraints**: `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, and `NOT NULL`.
* Demonstrate **relationships**: One-to-One, One-to-Many, and Many-to-Many.
* Implement with clean, modular, and scalable SQL code.

---

### 🏗️ **Database Design**

**Database Name:** `ecommerce_store`

**Key Entities:**

1. **Customers** – stores customer details
2. **Addresses** – linked to customers (one-to-many)
3. **Suppliers** – stores supplier contact details
4. **Categories** – defines product categories
5. **Products** – linked to suppliers and categories
6. **Orders** – created by customers (one-to-many)
7. **Order_Items** – junction table between orders and products
8. **Payments** – records multiple payments per order
9. **Inventory_Adjustments** – tracks stock changes
10. **Users** – system users or admins

---

### 🔗 **Relationships**

| Relationship Type | Example                                                |
| ----------------- | ------------------------------------------------------ |
| One-to-Many       | A customer can have many orders                        |
| Many-to-Many      | Products can belong to multiple categories             |
| One-to-One        | An order can have one billing and one shipping address |

---

### ⚙️ **Key Features**

* Referential integrity through **foreign key constraints**
* Automatic **stock updates** with SQL **trigger**
* Predefined **view** for quick order summary access
* Indexed columns for **query optimization**

---

### 📄 **Files**

| File                  | Description                                                            |
| --------------------- | ---------------------------------------------------------------------- |
| `ecommerce_store.sql` | Full SQL schema with database, tables, constraints, views, and trigger |
| `README.md`           | Documentation and setup guide                                          |

---


### ✍️ **Author**

**Awwal Fawas Adebisi**
📧 [adebisiamooh@gmail.com](mailto:adebisiamooh@gmail.com)
📂 GitHub: [AwwalFawas](https://github.com/AwwalFawas)

