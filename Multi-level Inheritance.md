# Exp.No:24  
## Multi-level Inheritance

---

### AIM  
To write a Python program to get the name, age, and location of a person and display them using multilevel inheritance.

---

### ALGORITHM

1. Define the Person class: Inside the Person class, define the init method (constructor) with two parameters: name and age. Inside the init method, assign the name to self.name and age to self.age.
2. Define the Employee class that inherits from the Person class: Inside the Employee class, define the init method (constructor) with three parameters: name, age, and location. Inside the init method, call the init method of the Person class using super() to initialize name and age. Assign location to self.location.
3. Define the DisplayDetails class that inherits from the employee class: Inside the DisplayDetails class, define the init method (constructor) with three parameters: name, age, and person_id. Inside the init method, call the init method of the PersonDetails class using super() to initialize name, age, and location.
4. Inside the DisplayDetails class, define the show_details method: Inside the show_details method, return a formatted string with self.name, self.age, and self.location.
5. Prompt the user to enter name (string), age (integer), and location (string).
6. Create an instance person of the DisplayDetails class, passing name, age, and location to the constructor.
7. Call the show_details method on the person object and print the result.
8. Terminate the program.

---

### PROGRAM
~~~
Reg.No: 212223060305
Nmae: Vishnu Priya E
class Person:
    def get_name(self, name):
        self.name = name

class Employee(Person):
    def get_age(self, age):
        self.age = age

class Location(Employee):
    def get_location(self, location):
        self.location =location 

    def display(self):
        print(self.name, self.age, self.location)

name = input()
age = int(input())
location  = str(input())

person = Location ()
person.get_name(name)
person.get_age(age)
person.get_location(location)
person.display()
~~~

### OUTPUT
<img width="895" height="294" alt="image" src="https://github.com/user-attachments/assets/a6ce6880-fbb1-4621-90b3-929f455df92e" />


### RESULT
Thus the program is created and verified.
