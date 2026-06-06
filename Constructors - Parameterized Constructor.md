# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

~~~
Reg.No: 212223090004
Name: D Dharshini priya

class person:
    def __init__(self,name,userid):
        self.name=name
        self.userid=userid
    def display(self):
        print(self.userid)
name=str(input())
userid=str(input())
obj=person(name,userid)
obj.display()
~~~ 


### OUTPUT
<img width="758" height="261" alt="image" src="https://github.com/user-attachments/assets/acc5738b-303d-488f-bdeb-c21c7ba5e413" />


### RESULT
Thus the program is created and verified.
