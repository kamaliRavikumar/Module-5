# Exp.No:25  
## Hierarchical Inheritance

---

### AIM  
To Write a Python program to get the name, attendance and Id of a student and check they are eligible for Placement using multiple inheritance
Note: grade >90 eligible student else Not Eligible student.

---

### ALGORITHM

1. Start the program.
2. Define a base class Student that stores the student’s name and ID.
3. Define another base class Attendance that stores the student’s attendance and grade.
4. Create a derived class PlacementCheck that inherits from both Student and Attendance.
5. In PlacementCheck, define a method check_eligibility() to check if grade > 90 → print “Eligible for Placement”, else → print “Not Eligible for Placement”.
6. Accept inputs: name, student ID, attendance, and grade from the user.
7. Create an object of PlacementCheck, call methods to display student details, and check placement eligibility.

---

### PROGRAM
```
class stud:
    def __init__(self,c):
        self.c=c
    def display(self,c):
        if c>90:
            print("Eligible for Placement")
        else:
            print("Not Eligible for Placement")
class par(stud):
    pass
a=input()
b=int(input())
c=int(input())
s=par(c)
print(a)
print(b)
s.display(c)

```

### OUTPUT  

<img width="1123" height="325" alt="Screenshot 2025-08-27 142740" src="https://github.com/user-attachments/assets/265f1652-f641-40f2-bedd-e69e24825aeb" />



### RESULT
Thus the Python program to get the name, attendance and Id of a student and check they are eligible for Placement using multiple inheritance is executed successfully.
