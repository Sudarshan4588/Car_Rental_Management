
# 🚗 Car Rental Management System

A **Java Swing-based GUI application** that provides a complete car rental platform. It supports multiple user roles including **Admin**, **Owner**, and **Customer**, enabling functionalities like car registration, booking, unbooking, billing, and real-time tracking of rental periods.

## 🧑‍💼 Admin Access

- **Username:** `admin`
- **Password:** `123`

## 🚀 How to Run
1. Clone the repository:
   git clone https://github.com/Sudarshan4588/Car_Rental_Management.git
   cd Car_Rental_Management

2.Open the project in any Java IDE ( VS Code).

3.Navigate to:src/gui/Runner.java

4.Run Runner.java to start the application

## ✨ Features

### 🔐 Role-Based Access
- **Register** as **Customer** or **Owner**
- All actions are handled and authorized through the **Admin Panel**

### 🧑‍💼 Owner Functionalities
- Register as a new owner
- Add, remove, and update car details
- View balance earned through rentals

### 👤 Customer Functionalities
- Register as a customer
- Book and unbook cars
- View and clear bills

### 🕒 Real-Time Clock
- Booking time and date are **automatically recorded**
- Unbooking calculates **return time** and updates billing

### 🛠️ Admin Panel
- Default credentials: `admin / 123`
- View all registered customers, owners, and cars
- Clear customer bills
- Check total balance of each owner

---

## 📅 Booking Flow

1. **Register as an Owner**
2. **Add a Car** with model, price, and other details
3. **Register as a Customer**
4. **Book a Car**
   - Time and date are **auto-captured**
5. **Unbook the Car**
   - Return time is auto-recorded
   - Bill is generated
6. **Admin clears the bill**
7. **Owner's balance is updated**


📌 Technologies Used

Java – Core language for application logic

Java Swing – GUI development

Serializable Interface – For object data persistence

File I/O – To store and retrieve data
