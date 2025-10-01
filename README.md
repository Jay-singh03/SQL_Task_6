# SQL_Task_6

# Database CompanyDB
-- Departments Table
-- Employees Table


1.Use scalar and correlated subqueries
* Use of Scalar subqueries with 'Salary' (outer query) column and 'salary'(inner query) column both in Employees Table
* Use of Correlated subqueries with 'Salary' (outer query) column and 'salary'(inner query) column both in Employees Table with a 'where Name = Employees.Name' condition


2.Use subqueries inside IN, EXISTS, =
* Use of 'IN' with 'DeptID' in Employees Table
* Use of 'Exists' with 'where d.DeptID = e.DeptID' condition as inner subquery in Departments Table depend on Employees Table
* Use of '=' with 'Salary' (outer query) column and 'salary'(inner query) column both in Employees Table
