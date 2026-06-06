# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.
2. Define a class Student with an init method to initialize name and age.
3. Define a method printDetail() to display the student's name and age.
4. Define a destructor del() to print a message when the object is deleted.
5. Create an object s1 of the Student class and call s1.printDetail() to display details.
6. Delete the object s1 using del s1.
7. Terminate the program.

---

### PROGRAM

```
~~~
#Reg.No: 212223090004
#Name: D Dharshini priya

class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def printDetail(self):
        print(f"My name is {self.name} and I am {self.age} years old.")

    def __del__(self):
        print(f"{self.name} student is deleted.")

s1 = Student("Vishvajit Rao", 22)
s1.printDetail()
del s1
~~~


```

### OUTPUT
<img width="1030" height="183" alt="image" src="https://github.com/user-attachments/assets/5a921c50-a05d-49cd-bb5c-554cce1fedb2" />



### RESULT
Thus the program is created and verified successfully.
