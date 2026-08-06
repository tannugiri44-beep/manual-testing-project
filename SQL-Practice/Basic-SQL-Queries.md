# Basic SQL Queries

## Create Table
```sql
CREATE TABLE Employee (
   EmpID NUMBER,
Name VARCHAR2(50),
Salary NUMBER
);
```

## Select All Records
```sql
SELECT * FROM Employee;
```

## Filter Records
```sql
SELECT * FROM Employee
WHERE Salary > 30000;
```

## Insert Record
```sql
INSERT INTO Employee (EmpID, Name, Salary)
VALUES (1, 'Rahul', 40000);
```
