

# **Hotel Management System 🏨**  

A **Java-based Hotel Management System** that allows users to book rooms, manage guests, and handle billing efficiently. This project is designed for both **hotel administrators** and **guests** to simplify hotel operations.  

---

## **Table of Contents**  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Project Structure](#project-structure)  
- [Installation](#installation)  
- [Running the Project](#running-the-project)  
- [Usage](#usage)  
- [Screenshots](#screenshots)  
- [Contributing](#contributing)  
- [License](#license)  

---

## **Features**  

✅ **User Authentication** – Secure login for admin and guests  
✅ **Room Booking** – Check room availability and book instantly  
✅ **Guest Management** – Store and retrieve guest details  
✅ **Billing System** – Automated bill generation and payment processing  
✅ **Room Service** – Additional services like food and laundry requests  
✅ **Admin Panel** – Manage rooms, bookings, and guests  

---

## **Technologies Used**  

| Technology  | Description  |
|-------------|-------------|
| **Java**  | Core language for backend logic  |
| **JDBC (Java Database Connectivity)**  | Connecting to MySQL database  |
| **MySQL**  | Storing hotel, guest, and booking data  |
| **Swing (Optional)**  | GUI-based interface for hotel management  |
| **File Handling**  | Storing temporary data (if database not used)  |

---

## **Project Structure**  

```
Hotel_Management/
│── src/                     # Source code files
│   │── models/              # Java classes for Room, Guest, Booking, etc.
│   │── database/            # Database connection and queries
│   │── ui/                  # UI components (if using Swing)
│── resources/               # Configuration files
│── HotelManagement.java     # Main entry point
│── README.md                # Project documentation
```

---

## **Installation**  

### **Prerequisites**  
Ensure you have the following installed:  
- [Java JDK (>= 8)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)  
- [MySQL Database](https://www.mysql.com/)  
- A code editor (Eclipse, IntelliJ IDEA, or VS Code)  

### **Clone the Repository**  
```bash
git clone https://github.com/Shreshtasingh/Hotel_management.git
```
```bash
cd Hotel_management
```

### **Compile the Java Files**  
```bash
javac -d bin src/*.java
```

---

## **Running the Project**  

### **Set Up MySQL Database**  
1. Start the MySQL server  
2. Create a database:  
   ```sql
   CREATE DATABASE hotel_db;
   ```
3. Import the initial database schema:  
   ```sql
   USE hotel_db;
   SOURCE database/init.sql;
   ```
4. Update database credentials in `database/DBConnection.java`  

### **Run the Application**  
```bash
java -cp bin HotelManagement
```

---

## **Usage**  

1. **Admin Login** – Manage rooms, guests, and bookings.  
2. **Guest Registration** – Register new guests and store details.  
3. **Book a Room** – Select available rooms and confirm booking.  
4. **Manage Room Services** – Order food, laundry, and cleaning services.  
5. **Billing System** – Generate invoices for guests during checkout.  

---

## **Screenshots**  

🚀 *You can add screenshots of the console output or GUI here* 🚀  

---

## **Contributing**  

Contributions are welcome! Follow these steps:  
1. **Fork** this repository.  
2. **Create** a new branch:  
   ```bash
   git checkout -b feature-name
   ```
3. **Make your changes** and commit:  
   ```bash
   git commit -m "Added new feature"
   ```
4. **Push** to your branch:  
   ```bash
   git push origin feature-name
   ```
5. **Open a Pull Request** and wait for approval.  

