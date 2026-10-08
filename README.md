# SQL_Course

<img width="895" height="483" alt="Screenshot 2026-10-02 at 8 04 56 PM" src="https://github.com/user-attachments/assets/0b606360-40bc-4f46-a5a7-899373fec59f" />

```
SELECT  DISTINCT grade_level FROM students

SELECT *
FROM students
WHERE grade_level IN (10,11,12)

SELECT *
FROM students

WHERE email LIKE '%.com'

```

```
SELECT student_name, grade_level
       CASE WHEN grade_level = 9 THEN 'Freshman'
            WHEN grade_level = 10 THEN 'Sophomore'
            WHEN grade_level = 1 THEN 'Junior'
            ELSE 'Senior' END AS student_class
FROm students

```
