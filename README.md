# Hotel-Management-SystemReports
1. Introduction*

The Hotel Management System is a simple C++ program used to manage hotel customer records. It allows users to store, view, search, and delete customer information. The system uses file handling to save data permanently.

---

## *2. Objectives of the Project*

* To learn *C++ structures and functions*
* To understand *file handling (read/write)*
* To create a *menu-driven program*
* To manage customer records efficiently
* To perform operations like add, display, search, and delete

---

## *3. Methodology / System Design*

* Uses a *structure (Hotel)* to store customer details
* Data is saved in a file *hotel.txt*
* Program is divided into functions:

  * Add Customer
  * Display Customers
  * Search Customer
  * Delete Customer
* Uses *file operations* (ifstream, ofstream)
* Menu-driven system for easy interaction

---

## *4. Implementation / Source Code*

* *addCustomer()* → Takes input and saves data to file
* *displayCustomers()* → Reads and displays all records
* *searchCustomer()* → Finds customer by room number
* *deleteCustomer()* → Deletes record using temporary file
* *main()* → Controls program using menu and switch-case

---

## *5. Conclusion*

This project demonstrates basic C++ concepts like structures, functions, and file handling. It provides a simple way to manage hotel records and can be further improved by adding advanced features like GUI or database support.
