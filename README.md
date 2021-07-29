# SQL-week-1

this week we did an intro dive into SQL using some of the following commands:

1. mysql> SELECT * FROM employees WHERE birth_date < '1965-01-01';

2. mysql> SELECT * FROM employees WHERE gender = 'F' AND hire_date > '1990-01-01';

3. mysql> SELECT emp_no, first_name, last_name, FROM employees WHERE last_name lIKE 'F%' LIMIT 50;

4. mysql> INSERT INTO employees VALUE(100, '1969-4-20', 'Ilean', 'Left', 'F', 2019-06-09');
   
   mysql> INSERT INTO employees VALUE(101, '1999-12-31', 'Yasmin', 'Twokay', 'F', '2020-04-01');

   mysql> INSERT INTO employees VALUE(102, '1995-05-26', 'Nicholas', 'Flammel', 'M', '2008-08-08');

5. mysql> UPDATE employees SET first_name = 'Bob' WHERE emp_no = 10023;

6. mysql> UPDATE employees SET hire_date = '2002-01-01' WHERE last_name LIKE 'P%' OR first_name LIKE 'P%';

7. mysql> DELETE FROM employees WHERE emp_no < 10000;

8. mysql> DELETE FROM employees WHERE emp_no = 10048;

  mysql> DELETE FROM employees WHERE emp_no = 10099;

  mysql> DELETE FROM employees WHERE emp_no = 10234;

  mysql> DELETE FROM employees WHERE emp_no = 20089;

  mysql> Select * FROM employees WHERE emp_no = 10048;

  mysql> Select * FROM employees WHERE emp_no = 10099;

  mysql> Select * FROM employees WHERE emp_no = 10234;

  mysql> Select * FROM employees WHERE emp_no = 20089;
