# SQL Organizational Troubleshooting and Data Filtering Project

## Overview
This project was completed on a **virtual machine** and focused on applying fundamental SQL concepts to troubleshoot and analyze data within an organization’s database.  
The objective was to identify system and employee information relevant to IT operations — such as locating machines with specific operating systems, isolating affected offices, and reviewing employee records for targeted actions.  

The tasks involved working with sample database tables like `machines` and `employees` to perform data extraction and filtering using the **`WHERE`** clause and **`LIKE`** operator.

---

## Tasks Overview

### **Task 1: List All Organization Machines and Their Operating Systems**
**Objective:**  
Display all machine records in the organization to review their operating systems.

**Explanation:**  
This provided a full overview of every device within the organization, helping IT staff understand the current system landscape before performing more targeted queries.


### **Task 2: Identify Devices Running OS 2 for Emergency Updates**
**Objective:**  
Find all machines running **OS 2**, which require an urgent update due to a detected vulnerability.

**Explanation:**  
The `WHERE` clause was used to filter results and display only the devices running OS 2.  
From the query results, it was determined that **80 devices** were using OS 2 and needed immediate updates.


### **Task 3: Retrieve Employee Records in the Finance Department**
**Objective:**  
Obtain employee records for those working in the **Finance Department**, including their office numbers.

**Explanation:**  
Using the `WHERE` clause, the query filtered the employee data to return only Finance department members.  
This information was used to issue notices regarding confidential financial data handling to those specific office locations.


### **Task 4: Identify Employee Using the Unresponsive Machine in Office South-109**
**Objective:**  
Determine which employee was assigned to the unresponsive machine located in **office South-109**.

**Explanation:**  
The query matched the machine’s office location with employee records to find the assigned user.  
The result showed that **employee “Jilansky” (Employee ID: 1010)** from the **Finance Department** was responsible for the affected device.


### **Task 5: Identify All Machines Located in the South Building**
**Objective:**  
Locate all machines in the **South building**, as IT reported widespread issues affecting systems in that area.

**Explanation:**  
The `LIKE` operator was used with the pattern `'south-%'` to find all office names starting with “South-”.  
This quickly isolated all devices located in the South building, allowing the IT team to flag them for troubleshooting and detailed inspection.


## What I Learned
Throughout this project, I developed practical SQL data analysis and troubleshooting skills, including:

- Using the **`SELECT`** statement to retrieve specific information from tables.  
- Applying the **`WHERE`** clause to filter and refine results based on conditions.  
- Utilizing the **`LIKE`** operator to search for patterns in text data.  
- Combining multiple filtering methods to locate affected devices, users, and departments.  
- Performing real-world troubleshooting scenarios using SQL queries.  


## 💻 Environment
- **Platform:** Virtual Machine (VM)  
- **Database Type:** Sample organizational SQL database  
- **Tables Used:** `machines`, `employees`  
- **Focus Areas:** Device management, employee data retrieval, troubleshooting affected systems  

---

## 📁 Summary
This project demonstrated how SQL can be applied in **organizational troubleshooting** to identify affected systems, employees, and office locations.  
By leveraging SQL filtering tools such as `WHERE` and `LIKE`, data-driven IT analysis and system management tasks can be performed efficiently — skills essential for roles in **cybersecurity**, **information analysis**, and **IT operations**.
