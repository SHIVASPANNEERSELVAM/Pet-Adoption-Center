# 🐾 Pet Adoption Center

## 📌 Project Overview
The **Pet Adoption Center** is a Java-based console application designed to streamline and manage the pet adoption process in an organized and efficient manner.

The system enables administrators to manage pet records while providing users with the ability to view, search, and adopt pets. It is built using a **layered architecture (DAO + Service + Model + UI)**, following standard software engineering principles.

This project demonstrates strong understanding of **Object-Oriented Programming (OOP)** and real-world application design patterns.

---

## 🎯 Objectives
- Build a structured system for managing pet adoption data
- Implement clean separation of concerns using layered architecture
- Demonstrate real-world usage of DAO and Service design patterns
- Apply core OOP principles in a practical application

---

## 🏗️ System Architecture

The project is divided into four main layers:

### 🔹 Presentation Layer
- `main.java`
- Handles user interaction via console
- Acts as the entry point of the application

### 🔹 Service Layer
- `Service.java`
- Contains business logic
- Validates and processes data before sending it to DAO

### 🔹 Data Access Layer (DAO)
- `DAO.java`
- Defines operations for data handling
- Abstracts storage logic from business logic

### 🔹 Model Layer
- `pets.java`
- Represents the pet entity
- Contains attributes and getter/setter methods

---

## 📁 Project Structure
```text
Pet-Adoption-Center/
│
├── main.java        # Console-based user interface
├── pets.java        # Model class (Pet entity)
├── DAO.java         # Data Access Object interface
├── Service.java     # Business logic layer
└── README.md
