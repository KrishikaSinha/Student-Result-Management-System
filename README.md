# 🎓 Student Result Management System

A Java application that collects student details, validates subject marks, calculates results, and displays pass/fail status. The project demonstrates the complete use of **Exception Handling**, including custom exceptions, try–catch, throw, throws, and finally.

---

## 🚀 Features

* Add new student details
* Validate marks (0–100) using a custom exception
* Calculate average of 3 subjects
* Display student details and result status
* Handle input errors gracefully using exception handling
* Supports multiple student records

---

## 🧠 Technologies Used

* Java
* Custom Exceptions
* Exception Handling (`try`, `catch`, `throw`, `throws`, `finally`)
* Arrays
* OOP Concepts

---

## 🗂 Project Structure

```
src/
 ├── InvalidMarksException.java
 ├── Student.java
 └── ResultManager.java
```

---

## ⚙ How It Works

* Marks entered by the user are first validated
* If marks are outside **0–100**, `InvalidMarksException` is thrown
* On valid input, average is calculated and result (Pass/Fail) is displayed
* `try–catch–finally` ensures clean error handling and resource closing

---

## 🧾 Sample Menu

```
===== Student Result Management System =====
1. Add Student
2. Show Student Details
3. Exit
```

---

## 📍 Sample Output

```
Enter Roll Number: 101
Enter Student Name: Alice
Enter Marks: 85 90 88
Student added successfully.
```

Invalid input example:

```
Enter Marks: -10
Error: Invalid marks for subject 1: -10
```

---

## 📌 Summary

This project demonstrates real-world application of Java exception handling with custom exception design, validation, and clean structured program flow. It builds reliable and error-safe execution using robust exception management.


