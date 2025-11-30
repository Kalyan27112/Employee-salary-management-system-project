# Employee-salary-management-system-project
# Employee Salary Management System (C Project)

## Project Overview
This is a console-based **Employee Salary Management System** written in C.  
It allows users to manage employee salary records by adding, updating, deleting, viewing, and listing employees.  
The system also calculates **gross salary** and **net salary** and stores all records in a binary file.

---

##  Features
-  Add new employee  
-  View employee details / payslip  
-  Update employee information  
-  Delete employee record  
-  List all employees  
-  Stores data in `employees.dat`  
-  Automatically calculates:
  - Gross Salary = Basic + Allowances  
  - Net Salary   = Gross – Deductions  

---

##  Technologies Used
- **Language:** C  
- **Compiler:** GCC / Dev-C++  
- **Files:**
  - `main.c` – main logic & menu
  - `salary.c` – function implementations
  - `salary.h` – structure & declarations
  - `employees.dat` – auto-created database

---

##  How to Compile & Run

### **Using Dev-C++**
1. Open Dev-C++  
2. Create a new **Console Application (C Project)**  
3. Add these files to the project:
   - `main.c`
   - `salary.c`
   - `salary.h`
4. Press **F11** to Compile and Run

---

### **Using GCC (Command Line)**
```bash
gcc main.c salary.c -o salary
./salary
