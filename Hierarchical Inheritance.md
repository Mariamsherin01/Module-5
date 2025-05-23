# Exp.No:25  
## Hierarchical Inheritance

---

### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor`.

---

### ALGORITHM

1. **Begin the program.**
2. **Create a class Details** with an `__init__` method to initialize three attributes: `id`, `name`, and `gender`.
3. **Define a method display_details()** to print the values of `id`, `name`, and `gender`.
4. **Create a class Employee** that inherits from the `Details` class. 
   - Add two additional attributes: `company` and `department`.
   - Override the `display_details()` method to print the employee-specific attributes (`company` and `department`) along with the inherited details.
5. **Create a class Doctor** that also inherits from the `Details` class. 
   - Add two additional attributes: `hospital` and `department`.
   - Override the `display_details()` method to print the doctor-specific attributes (`hospital` and `department`) along with the inherited details.
6. **Accept input** for employee and doctor details.
7. **Create objects of Employee and Doctor** using the input.
8. **Call the `display_details()` method** for both objects to print the details.
9. **Terminate the program.**

---

### PROGRAM
```
reg.no: 212222060143
name: Mariam Sherin
class Details:
    def __init__(self):
        self.eid=eid
        self.ename=ename
        self.egen=egen
        self.ecomp=ecomp
        self.edept=edept
        self.did=did
        self.dname=dname
        self.dgen=dgen
        self.dhos=dhos
        self.ddept=ddept
class Employee(Details):
    def showe(self):
        print("Id: ",self.eid)
        print("Name: ",self.ename)
        print("Gender: ",self.egen)
        print("Company: ",self.ecomp)
        print("Department: ",self.edept)
class Doctor(Details):
    def showd(self):
        print("Id: ",self.did)
        print("Name: ",self.dname)
        print("Gender: ",self.dgen)
        print("Hospital: ",self.dhos)
        print("Department: ",self.ddept)
eid=int(input())
ename=input()
egen=input()
ecomp=input()
edept=input()
did=int(input())
dname=input()
dgen=input()
dhos=input()
ddept=input()
print("Employee Object")
e=Employee()
e.showe()
print("\nDoctor Object")
d=Doctor()
d.showd()
    

```

### OUTPUT  

![image](https://github.com/user-attachments/assets/2ea2b851-852a-44cc-af4b-877153a5d392)




### RESULT
Thus, The Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor` was implemented and executed successfully.
