# 📘 MongoDB Employee Database Project

## 📖 Project Description
This project demonstrates the practical use of **MongoDB Compass** to manage an employee database. It involves creating a database, importing data, and performing various CRUD (Create, Read, Update, Delete) operations and projections.

## 🛠️ Technologies Used
*   **Database:** MongoDB
*   **Interface:** MongoDB Compass
*   **Language:** JSON (Data Storage)

## ✨ Features & Tasks Completed
1.  **Database Setup:** Created `companyDB` database and `employees` collection.
2.  **Data Import:** Imported 20 employee records from a JSON file.
3.  **Data Queries:**
    *   Fetched documents based on filters (e.g., Department = "IT").
    *   Filtered records based on numerical values (e.g., Salary > 70000).
4.  **Data Insertion:**
    *   **Insert One:** Added a single new employee document.
    *   **Insert Many:** Added an array of 3 new employee documents at once.
5.  **Data Projection:** Retrieved specific fields (like Name and Email) while hiding others to optimize data viewing.

##  Project Structure

```text
mongodb-employee-project/
│
├──  employees.json              # Original 20 records imported
├── 📄 admin.employees.json        # Exported backup data
├── 📄 queries_used.txt            # List of queries run during the project
├──  project_report.docx         # Detailed project report
├── 📁 screenshots/                # Visual proof of project execution
│   ├── ️ compass_home.png
│   ├── 🖼️ query_results.png
│
└── 📄 README.md                   # This file
