# 🛒 Electronics eCommerce Platform

This project is a full-stack eCommerce website for electronics shopping, developed as part of my CSCI 4320 Software Engineering course. It includes user registration, product browsing, cart management, checkout, and email notifications — all within a secure, database-driven web platform.

---

## 🔧 Features
- ✅ User login/registration with email verification
- 🛒 Add to cart, update quantity, and remove items
- 📦 Checkout flow with simulated credit card processing
- 📧 Email notifications on:
  - New user registration
  - Order confirmation
  - Shipping updates
  - Back-in-stock alerts
- 🛠️ Admin dashboard to manage products, inventory, and order status

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Backend:** Java (JDK 8+), JSP, Servlets, JDBC  
- **Database:** MySQL  
- **Tools:** Eclipse EE, Apache Tomcat, Maven

---

## 🖥️ How to Run
1. Set up MySQL and import the SQL schema from `/databases/mysql_query.sql`
2. Configure email SMTP settings (for Gmail app password-based auth)
3. Import project into Eclipse EE
4. Build with Maven: `clean install`
5. Run with Tomcat server at `http://localhost:8080/shopping-cart/`

---

## 📌 Default Credentials (for testing)
- **Admin**: `admin@gmail.com` / `admin`  
- **User**: `guest@gmail.com` / `guest`

---

## 🎯 Project Context
This project simulates a real-world eCommerce workflow with full user interaction and admin oversight. My contributions included building core shopping logic, integrating email features, and configuring the servlet-based backend using Java.

---

## 📫 Contact
📧 avlonvonwalter@gmail.com  
🔗 [GitHub Profile](https://github.com/AvlonVonWalter)



