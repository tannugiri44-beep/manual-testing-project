# Basic SQL Queries

## Create Table
```sql
CREATE TABLE Employee (
    EmpID INT,
    Name VARCHAR(50),
    Salary INT
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
