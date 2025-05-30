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
```
Reg no-212223020028
Name-Tharani devi.G
write your code
class Person:
    def __init__(self,name,uid):
        self.name=name
        self.uid=uid
        print(self.uid)
p=Person(input(),input())
```

### OUTPUT

![MODULE 5A](https://github.com/user-attachments/assets/7ce6a9fc-a6b6-4c4f-b37b-60973623b2bb)


### RESULT
This program for code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person is successfully executed.
