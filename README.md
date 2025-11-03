# 🕹️ Java Gaming Store System – GUI Application

A complete **Java-based Gaming Store Management System** with a fully functional **Graphical User Interface (GUI)** built in **Eclipse IDE**.  
The system allows **managers**, **employees**, and **customers** to interact with a shared inventory, process purchases, and manage stock operations efficiently.  

Developed by **Tysier Zidan** as part of the *Object-Oriented Programming* final project at Ruppin Academic Center.

---

## 🧩 Project Overview

This desktop application simulates a digital game store that manages customers, products, employees, and suppliers.  
It was designed with an emphasis on **object-oriented programming**, **multi-threading**, and **file-based data persistence**.

The GUI supports three main user roles:

| Role | Username | Password | Description |
|------|-----------|-----------|-------------|
| **Manager** | `Tysier` | `Tysier123` | Full access to add, remove, update, and view all products, suppliers, and sales records. |
| **Employee** | `Kosay` | `Kosay123` | Acts as a cashier, processes customer orders, verifies payments, and tracks working hours. |
| **Customer** | `Gabi` | `Gabi123` | Can register, browse available games, make purchases, and view personal order history. |

---

## ⚙️ Key Features

- 💼 **Manager Section**
  - Add new products or suppliers  
  - Update product prices  
  - View purchased products and supplier data  
  - Display complete warehouse inventory  

- 🧾 **Employee Section**
  - Process and confirm customer orders  
  - Handle pending orders and validate transactions  
  - Track employee working hours and wages dynamically  

- 🎮 **Customer Section**
  - Register as a new customer or log in as an existing one  
  - Browse available products by category  
  - Add items to cart and complete purchases  
  - Handle order confirmation and re-entry for failed payments  

- 💾 **File-based storage**
  - All data (customers, orders, products, and suppliers) are saved and loaded from `.txt` files  
  - No external database is required  

- ⚡ **Multi-threading**
  - Used to simulate concurrent operations (e.g., employee tasks, order handling)

- 🧠 **OOP Structure**
  - Classes for `Manager`, `Employee`, `Customer`, `Supplier`, and `Product`  
  - Inheritance, abstraction, and encapsulation principles applied throughout  
  - Uses **`Vector`** instead of `List` to manage collections  

---

## 🖥️ GUI Overview

Developed using **Java Swing** inside **Eclipse IDE**.  
Each role (Manager, Employee, Customer) is accessed through the **Main Menu**:

1.Manager Section

2.Employee Section

3.Customer Section

4.Exit


Each option opens a separate GUI window with relevant controls, text fields, and action buttons.

---

## 🧪 How to Run

1. **Download** or **clone** this repository.  
2. Open **Eclipse IDE** and **Import → Existing Java Project**.  
3. Browse to the project folder and finish import.  
4. Open and run the file:

GameStoreManagementSystem.java

*(or `Main.java`, depending on your setup — it launches the GUI menu)*  
5. Use one of the credentials above to log in and explore each section.  

---

## 📁 Project Structure

Java-Gaming-Store/
│
├── src/
│ ├── GameStoreManagementSystem.java
│ ├── Manager.java
│ ├── Employee.java
│ ├── Customer.java
│ ├── Supplier.java
│ ├── Product.java
│ ├── GUI/ (contains all GUI frames and windows)
│
├── data/
│ ├── products.txt
│ ├── suppliers.txt
│ ├── orders.txt
│ ├── customers.txt
│
├── FinalProjectJavav3.zip (complete project archive)
└── Inventory x pdf_clarification.pdf (documentation and login guide)


---

## 🎥 Demonstration

A video demonstration or screenshots can be added here, showing:
- Main Menu  
- Login Window  
- Manager and Customer interfaces  
- Example of a purchase flow  

*(Add images in `/images` and link them here)*

---

## 👨‍💻 Author

**Tysier Zidan**  
B.Sc. Computer Engineering – Ruppin Academic Center  
📍 Akko, Israel  
📧 zidantysier87@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/tysier-zidan-bb1565331)

---

