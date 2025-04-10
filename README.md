# ☕ Cafe Management System

A web-based application to manage the daily operations of a cafe—order placement, billing, menu handling, and user roles. Developed using **Java (Servlets, JSP)**, **MySQL**, and **Bootstrap**.

---

## 📌 Features

- 🔐 **User Authentication**: Secure login & registration for Admin and Customers.
- 📋 **Menu Management**: Add, update, delete items (Admin).
- 🛒 **Order Placement**: Customers can browse items, add to cart, and place orders.
- 🧾 **Billing System**: Automatically calculates total and generates printable bill.
- 📦 **Order Tracking**: Orders and items are stored and managed in the database.
- 📁 **Role-Based Access**: Admin vs Customer views.

---

## 🛠️ Technologies Used

| Component       | Technology                     |
|----------------|----------------------------------|
| Frontend        | HTML, CSS, Bootstrap 5           |
| Backend         | JSP, Java Servlets               |
| Database        | MySQL                            |
| Server          | Apache Tomcat                    |
| IDE             | NetBeans                         |
| Build Tool      | Maven                            |
| Java Version    | Java 17                          |

---

## 💾 Database Schema

**Tables:**
- `users`: Stores user credentials and roles.
- `menu`: Holds cafe items.
- `orders`: Main order information.
- `order_items`: Items linked to an order.

📂 Sample Data included in `schema.sql`.

---

## 🧪 Sample Credentials

```bash
Admin:
Email: admin@cafe.com
Password: admin123

Customer:
Email: john@example.com
Password: johnpass
