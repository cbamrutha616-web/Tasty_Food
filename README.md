# 🍔 Tasty Foods - Full Stack Food Delivery Application

A modern and responsive **Full Stack Food Delivery Web Application** that allows users to browse restaurants, explore menus, add food items to the cart, place orders, and manage their profiles. The application is developed using **Java, JDBC, Servlets, JSP, MySQL, HTML, CSS, and JavaScript**, following the MVC architecture for clean and scalable development. README files commonly include project overview, features, technologies, setup steps, and screenshots to help users understand and run the project. :contentReference[oaicite:0]{index=0}

---

## 📌 Features

### 👤 User Module
- User Registration & Login
- Secure Password Authentication
- User Profile Management

### 🍽️ Restaurant Module
- View Restaurants
- Restaurant Search
- Restaurant Details
- Restaurant Ratings

### 📖 Menu Module
- Browse Food Items
- Food Categories
- Food Details
- Price & Description

### 🛒 Cart Module
- Add to Cart
- Update Quantity
- Remove Items
- View Total Price

### 📦 Order Module
- Place Orders
- Order Confirmation
- Order History
- Track Order Status

### ⭐ Reviews & Ratings
- View Restaurant Ratings
- Customer Feedback

### 🔒 Admin Features
- Manage Restaurants
- Manage Menu Items
- View Customer Orders
- Update Order Status

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- JSP

### Backend
- Java
- JDBC
- Servlets

### Database
- MySQL

### Server
- Apache Tomcat 10

### IDE
- Eclipse IDE

### Architecture
- MVC (Model-View-Controller)

---

## 📂 Project Structure

```
TastyFoods/
│
├── src/
│   ├── model/
│   ├── dao/
│   ├── daoimpl/
│   ├── servlet/
│   └── util/
│
├── WebContent/
│   ├── images/
│   ├── css/
│   ├── js/
│   ├── jsp/
│   └── index.jsp
│
├── database/
│   └── tastyfoods.sql
│
└── README.md
```

---

## 💻 Software Requirements

- Java JDK 17+
- Eclipse IDE
- Apache Tomcat 10+
- MySQL Server
- MySQL Workbench

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/TastyFoods.git
```

### 2. Import Project

- Open Eclipse
- Import Existing Dynamic Web Project

### 3. Configure Database

Create a database:

```sql
CREATE DATABASE tasty_foods;
```

Import the SQL file.

### 4. Update Database Credentials

Edit your database connection class:

```java
String url = "jdbc:mysql://localhost:3306/tasty_foods";
String username = "root";
String password = "yourpassword";
```

### 5. Configure Apache Tomcat

- Add Tomcat Server
- Deploy Project

### 6. Run

```
http://localhost:8080/TastyFoods/
```

---

## 📸 Application Modules

- 🏠 Home Page
- 👤 Login & Registration
- 🍽️ Restaurants
- 📖 Menu
- 🛒 Cart
- 💳 Checkout
- 📦 Order History
- ⭐ Ratings
- 👨‍💼 Admin Panel

---

## 🗄️ Database Tables

- Users
- Restaurants
- Menu
- Orders
- OrderItems
- Cart
- Reviews

---

## 🚀 Future Enhancements

- Online Payment Integration
- Live Order Tracking
- Email Notifications
- Coupon System
- Wishlist
- Dark Mode
- AI Food Recommendation
- Mobile Responsive Improvements

---

## 👩‍💻 Developed By

**Amrutha C.B**

Electronics & Instrumentation Engineering

Aspiring Full Stack Java Developer

### Skills

- Java
- JDBC
- Servlets
- JSP
- MySQL
- HTML
- CSS
- JavaScript

---

## 📧 Contact

Email: your-email@example.com

LinkedIn: https://linkedin.com/in/yourprofile

GitHub: https://github.com/yourusername

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!

Happy Coding! 🚀
