# Employee Management System (Python OOP Project)

## 📌 Project Overview

The Employee Management System is a menu-driven Python application developed using Object-Oriented Programming (OOP) concepts. It allows users to create and manage Person, Employee, and Manager records through an interactive console interface.

This project demonstrates the use of classes, objects, inheritance, method overriding, and the `super()` function in Python.

---

## 🚀 Features

- Create a Person record
- Create an Employee record
- Create a Manager record
- Display stored Person details
- Display stored Employee details
- Display stored Manager details
- Menu-driven user interface
- Exit option to terminate the application

---

## 🛠️ OOP Concepts Used

### 1. Classes and Objects
- `Person`
- `Employee`
- `Manager`

### 2. Inheritance
- `Employee` inherits from `Person`
- `Manager` inherits from `Employee`

### 3. Method Overriding
- Each class overrides the `display()` method to show specific details.

### 4. super()
- Used to call constructors of parent classes.

---

## 📂 Project Structure

```
Employee-Management-System/
│
├── employee_management.py
└── README.md
```

---

## ▶️ How to Run

### Prerequisites

- Python 3.x installed

### Run the Program

```bash
python employee_management.py
```

---

## 💻 Example Output

```text
--- Python OOP Project: Employee Management System ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Show Details
5. Exit

Enter your choice: 1

Enter Name: John Doe
Enter Age: 30

Person created with name: John Doe and age: 30.
```

---

## 📖 Class Diagram

```text
Person
  │
  └── Employee
          │
          └── Manager
```

---

## 🎯 Learning Outcomes

- Understanding Object-Oriented Programming
- Working with Inheritance
- Using Method Overriding
- Implementing Menu-Driven Applications
- Managing Data with Python Classes

---

## 🔧 Technologies Used

- Python 3
- Object-Oriented Programming (OOP)

---

## 👨‍💻 Author

Disha Thakkar

GitHub Portfolio Project
