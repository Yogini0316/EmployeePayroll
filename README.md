# EmployeePayroll
# 👩‍💼 Employee Payroll Management System

A simple Java-based Employee Payroll Management System that helps manage employee records, salaries, and payroll generation efficiently.

---

## 🚀 Features

- Add, update, and delete employee records
- Calculate and display salary and deductions
- Generate monthly payroll reports
- Store employee data in a MySQL(SQLite) database
- User-friendly GUI using Java Swing (if applicable)

---

## 🛠️ Tech Stack

- **Programming Language**: Java
- **GUI (Optional)**: Java Swing / JavaAWT
- **Database**: SQLite
- **IDE**: IntelliJ / Eclipse / NetBeans

---

## 🗃️ Database Setup

1. Create a SQLite database named:
   Empnet.sqlite
2. Run the following to create tables:
   
CREATE TABLE employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    department VARCHAR(100),
    designation VARCHAR(100),
    salary DECIMAL(10,2),
    date_joined DATE
);

3. Update your Database Credentials in the code :
String url = "jdbc:sqlite:C:/path/to/your/database/empnet.sqlite";

-----

## 🧑‍💻 How to Run

1. clone this Repositary
  git clone https://github.com/Yogini0316/EmployeePayroll.git

  cd EmployeePayroll
3. Open in your IDE and configure database connector
4. For Netbeans right click project and run it
5. For IntelliJ Run the main Java class
   javac main class
   java main

## 🙋‍♀️ Author
Yogini Sonawane
GitHub: Yogini0316
   
   




