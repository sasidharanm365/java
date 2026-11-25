# java
# 🏢 Visitor Management System

## 📌 Project Overview

The **Visitor Management System** is a Java-based application developed to manage visitor information efficiently. It provides a user-friendly graphical interface using Java AWT, allowing users to add, view, search, and delete visitor records.

The system maintains visitor details in an organized manner and reduces the manual effort involved in traditional visitor record management.

## 🎯 Objectives

- To simplify visitor registration and record management.
- To reduce manual paperwork and human errors.
- To provide quick searching and retrieval of visitor details.
- To maintain organized visitor records.
- To demonstrate Java Object-Oriented Programming concepts.

## 🛠️ Technologies Used

- **Programming Language:** Java
- **JDK Version:** JDK 21
- **GUI Framework:** Java AWT (Abstract Window Toolkit)
- **Data Storage:** ArrayList
- **Event Handling:** ActionListener, WindowAdapter
- **Date Validation:** Java DateTimeFormatter
- **IDE:** Any Java-supported IDE (Eclipse, IntelliJ IDEA, or VS Code)

## ⚙️ Features

1. **Add Visitor**
   - Register new visitors.
   - Enter Visitor ID, Name, Purpose, Visit Date, and Contact Number.
   - Validate visitor information.
   - Prevent duplicate Visitor IDs.

2. **View All Visitors**
   - Display all registered visitor records.
   - View visitor information in an organized format.

3. **Search Visitor**
   - Search visitors using their unique Visitor ID.
   - Display matching visitor information.

4. **Delete Visitor**
   - Delete visitor records using Visitor ID.
   - Display confirmation messages.

5. **Clear Fields**
   - Clear all input fields for new entries.

6. **Exit**
   - Close the application safely.

## 🏗️ System Architecture

The application consists of the following modules:

- Visitor Entry Management Module
- Visitor Directory Module
- Visitor Search Module
- Visitor Deletion Module
- Data Management Module
- Input Handling Module
- Graphical Interface Module
- System Control Module

## 📂 Project Structure

```text
Visitor-Management-System/
│
├── VisitorManagementAWT.java
│
├── screenshots/
│   ├── home-page.png
│   ├── add-visitor.png
│   ├── login-successful.png
│   ├── view-visitor.png
│   ├── search-visitor.png
│   └── delete-visitor.png
│
└── README.md
```

## ▶️ How to Run the Project

### Step 1: Install Java

Install JDK 21 or later and configure the Java environment.

### Step 2: Clone the Repository

```bash
git clone <your-github-repository-link>
```

### Step 3: Open the Project

Open the project folder in VS Code, Eclipse, or IntelliJ IDEA.

### Step 4: Compile the Java Program

```bash
javac VisitorManagementAWT.java
```

### Step 5: Run the Application

```bash
java VisitorManagementAWT
```

The Visitor Management System graphical interface will open.

## 🔐 Input Validation

The application includes validation mechanisms to maintain accurate visitor information.

- Visitor ID must be a non-negative integer.
- Visitor IDs must be unique.
- Visitor names must contain only letters and spaces.
- Purpose of visit cannot be empty.
- Visit date must follow the DD/MM/YYYY format.
- Contact number must contain exactly 10 digits.

## 💾 Data Storage

Visitor information is stored dynamically using Java's **ArrayList** collection.

Each visitor record contains:

- Visitor ID
- Visitor Name
- Purpose of Visit
- Visit Date
- Contact Number

**Note:** The current implementation uses in-memory storage. Visitor records are not permanently saved and will be lost when the application is closed.

## 📸 Project Screenshots

### Home Page
<!-- Add your home page screenshot here -->

### Add Visitor
<!-- Add your add visitor screenshot here -->

### View All Visitors
<!-- Add your view visitor screenshot here -->

### Search Visitor
<!-- Add your search visitor screenshot here -->

### Delete Visitor
<!-- Add your delete visitor screenshot here -->

## 🚀 Future Enhancements

- Integrate MySQL database for permanent data storage.
- Implement login authentication and role-based access.
- Generate visitor reports in PDF or Excel format.
- Add advanced search and filtering options.
- Implement QR code-based visitor registration.
- Develop an enhanced interface using Java Swing or JavaFX.

## 🎓 Academic Details

- **Project Title:** Visitor Management System
- **Course Code:** EGB1201 – Java Programming
- **Department:** Electronics and Communication Engineering
- **Institution:** K. Ramakrishnan College of Engineering (Autonomous)
- **Academic Year:** 2025–2026

## 👨‍💻 Developer

**M. Sasi Dharan**

Department of Electronics and Communication Engineering  
K. Ramakrishnan College of Engineering (Autonomous)

## 📚 References

- Oracle Java Documentation
- Java Platform, Standard Edition 21 API Specification
- Herbert Schildt – Java: The Complete Reference
- Kathy Sierra & Bert Bates – Head First Java
- Baeldung – Java Date and Time API

---

⭐ **If you find this project useful, consider giving the repository a star!**
