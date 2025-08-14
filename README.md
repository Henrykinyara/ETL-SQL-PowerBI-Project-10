# ETL-SQL-PowerBI-Project-10
End-to-end data project with ETL pipeline, SQL database, and Power BI dashboard

# AdventureWorks Human Resources BI Project

## Project Overview
This project uses the **AdventureWorks** sample database to create a unified view combining multiple Human Resources tables.  
The goal is to prepare a single dataset for Power BI reporting that includes employee details, department history, and pay information.

---

## Data Sources
The following tables from **AdventureWorks** are used:
1. `HumanResources.Department`
2. `HumanResources.Employee`
3. `HumanResources.EmployeeDepartmentHistory`
4. `HumanResources.EmployeePayHistory`

---

## Steps Performed
1. **Create a View**  
   - Combine all 4 tables into a single view: `View_HumanResources`
   - Include all relevant employee-related fields

2. **Add Calculated Columns**  
   - **Annual Salary** = `Rate * 2080`  
   - **Years Worked** = Difference between current date and hire date (targeting 10 years in dataset)  
   - **Refresh Date** = Current system date/time

3. **Load into Power BI**  
   - Connect to the created SQL Server view  
   - Build a Power BI report using creativity and discretion

---

## Power BI Report
The report should provide:
- Employee details and salary insights  
- Department distribution and history  
- Work tenure analysis  
- Interactive filters and visualizations

---

##Tools & Technologies
- **Microsoft SQL Server** (AdventureWorks database)
- **SQL Server Management Studio (SSMS)**
- **Power BI Desktop**

---

## How to Run the Project
1. Open **AdventureWorks** database in SQL Server.  
2. Create the `View_HumanResources` using the provided SQL script.  
3. Open Power BI Desktop and connect to SQL Server.  
4. Load the view and build your report.

---


