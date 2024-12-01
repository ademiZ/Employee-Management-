Employee Management System
This JavaFX application allows users to manage a list of employees and their salaries. The system supports three types of employees: Full-time, Part-time, and Contractors, each with a unique salary calculation method. The application provides a graphical interface to view, add, calculate, and remove employees from the list.

Features
Add employees with specific attributes:
Full-Time: Fixed annual salary.
Part-Time: Hourly wage and hours worked.
Contractor: Hourly rate and maximum hours per month.
Display employees in a table:
Name
Type (Full-Time, Part-Time, Contractor)
Calculated Salary
Validate inputs to ensure correctness (e.g., positive values for salary and hours).
Remove employees from the table.
Automatically calculate salaries for all employees.
Requirements
Java: JDK 11 or higher
JavaFX: JavaFX 11 or higher
Setup and Run
Clone the repository:
bash
Копировать код
git clone https://github.com/yourusername/employee-management-system.git
cd employee-management-system
Open the project in your IDE (e.g., IntelliJ, Eclipse) and configure JavaFX.
Run the Main.java file.
Sample Inputs
Full-Time:
Name: John Doe
Type: Full-Time
Annual Salary: 60,000
Part-Time:
Name: Jane Smith
Type: Part-Time
Hourly Wage: 20
Hours Worked: 30
Contractor:
Name: Mark Johnson
Type: Contractor
Hourly Rate: 25
Max Hours: 100
