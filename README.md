# Student-Result-Management-System
This Java program manages student results using exception handling. It stores student data, validates marks with a custom InvalidMarksException, computes averages, and displays pass/fail results. It uses throw, throws, try-catch, and finally for safe execution.


# 📚 City Library Digital Management System

A Java-based console application designed to digitally manage library operations using **File Handling** and the **Java Collections Framework**. It supports adding books and members, issuing and returning books, and maintaining persistent records through file storage.

---

## 🚀 Features

* Add new books and members
* Issue and return books
* Search for books by title, category, or author
* Sort books using Comparable and Comparator
* Persistent data storage using File I/O
* Efficient data management using Maps and Lists

---

## 🧠 Technologies Used

* Java
* Collections Framework (Map, List)
* Comparable and Comparator
* File Handling (Buffered I/O, Serialization)

---

## 🗂 Project Structure

```
src/
 ├── Book.java
 ├── Member.java
 └── LibraryManager.java
```

---

## ⚙ How It Works

* All books and members are stored in Maps with their IDs as keys
* Issued books are tracked using Lists
* Data is loaded from files at startup and saved on exit
* Sorting and searching are implemented using Java Collections

---

## 💾 File Storage

* `books.txt` — Contains all book data
* `members.txt` — Contains all member data

Both are created automatically if missing.

---

## 📌 Sample Menu

```
===== City Library Digital Management System =====
1. Add Book
2. Add Member
3. Issue Book
4. Return Book
5. Search Books
6. Sort Books
7. Exit
```

---

## 📍 Summary

This project demonstrates real-world implementation of Java File Handling and Collections. It provides a structured and persistent system to manage books, members, and transactions efficiently using Maps, Lists, Comparable, Comparator, and buffered I/O operations.

---

## 👩‍💻 Author

Krishika Sinha
B.Tech CSE, K.R. Mangalam University
