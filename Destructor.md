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
reg.no: 212222060143
name: Mariam Sherin
class Student:
    def __init__(self, name):
        print("Inside Constructor")
        print("Object initialized")
        self.name = name

    def greet(self):
        print(f"Hello, my name is {self.name}")

    def __del__(self):
        print("Inside destructor")
        print("Object destroyed")

student = Student("Emma")
student.greet()
del student

```

### OUTPUT
![image](https://github.com/user-attachments/assets/3e320115-7ce9-4e2c-a935-bf16016592a1)


### RESULT
Thus, The Python class `Student` with a destructor was implemented and executed successfully.
