## Payroll System Design

### Problem Statement:
Develop a simple payroll system for a company that manages employees' information, calculates their monthly salaries, and generates pay stubs.

### Requirements:
1. The system should allow the addition of different types of employees such as full-time employees, part-time employees, and contractors.
2. Each employee should have attributes such as name, employee ID, hourly rate/salary, and type (full-time, part-time, contractor).
3. The system should be able to calculate monthly salaries based on the hours worked for part-time employees and the monthly salary for full-time employees and contractors.
4. Full-time employees receive a fixed monthly salary, part-time employees are paid based on the hours worked multiplied by their hourly rate, and contractors receive a fixed amount per month.
5. Generate pay stubs for each employee that include their name, employee ID, type, hours worked (if applicable), hourly rate/salary, and the calculated monthly salary.
6. Ensure proper encapsulation by using access modifiers for class attributes and methods.
7. Implement error handling for scenarios such as invalid input for hourly rates or hours worked.
8. Use inheritance to model different types of employees and promote code reuse.
9. Design the system to be easily extensible to accommodate new employee types or salary calculation methods in the future.

### Design:
1. Identify classes such as Employee, FullTimeEmployee, PartTimeEmployee, and Contractor.
2. The Employee class should contain common attributes and methods shared by all employee types.
3. Implement subclasses for each employee type, inheriting from the Employee class and overriding methods as necessary.
4. Use appropriate data structures to store employee information and manage payroll calculations.
5. Implement methods to calculate monthly salaries based on the employee type.
6. Design a mechanism to generate pay stubs for each employee, ensuring that relevant information is included.
7. Encapsulate data and behavior within classes, utilizing access modifiers to control access to class members.
8. Implement error handling to handle invalid input and edge cases gracefully.
9. Design the system with flexibility in mind to accommodate future changes and additions.
