# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
class Student:
    def __init__(self, name):
        print('Inside Constructor')
        self.name = name
        print('Object initialized')
    def show(self):
        print('Hello, my name is', self.name)
    def __del__(self):
        print("Inside destructor\nObject destroyed")
s1 = Student('Emma')
s1.show()
del s1
```

### OUTPUT

<img width="1014" height="285" alt="Screenshot 2025-08-27 142314" src="https://github.com/user-attachments/assets/25d331e4-3efc-4e7e-8d6b-2b1998515a34" />

### RESULT
Thus to create a Python class `Student` with a destructor is executed successfully.
