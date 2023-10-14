## 8. Given the following Python code: 
```class MyClass: 
variable = 10 
obj1 = MyClass() 
obj2 = MyClass() 
obj2.variable = 20 
print(obj1.variable) 
print(obj2.variable) 
What will be the output?
```
### Output
10 
20
obj1 and obj2 are instances of the MyClass class.
variable is a class variable shared among all instances of the class.
obj2.variable = 20 sets the variable for obj2 only.
Therefore, when we print obj1.variable, it still uses the class variable variable (10), and when we print obj2.variable, it uses the modified value (20) for obj2.
____
## 9. Given the following Python code: 
```class Person: 
def __init__(self, name): 
self.name = name
person1 = Person("Alice") 
person2 = Person("Bob") 
print(person1.name) 
print(person2.name) 
What will be the output?
```
### Output
Alice
Bob
We create two instances of the Person class: person1 and person2.
When creating each instance, we pass a name to the __init__ method, which sets the name attribute for that instance.
We then print the name attribute for each instance, which will give us the names "Alice" and "Bob" for person1 and person2, respectively.
____
## 10. Given the following Python code: 
```class A: 
  def __init__(self, x): 
  self.x = x 
class B(A): 
  def __init__(self, y): 
    self.y = y 
obj = B(10) 
print(obj.x, obj.y) 
What will be the output? 

```
### Output
10 10
Class B is derived from class A using inheritance.
The __init__ method in class B takes a parameter y and sets it as an attribute y for instances of class B.
Inside __init__ of class B, we call __init__ of class A with a value 10, which sets self.x = 10.
Therefore, when we create an instance of class B with B(10), self.y is set to 10 by the __init__ method of class B, and self.x is set to 10 by the __init__ method of class A (which is called from class B).
____
## 11. print(obj3.count) 
### What will be the output? 
In Python, a class is a: 
```a) Blueprint for creating objects ```
____
## 12. In object-oriented programming, encapsulation means:
```b) Hiding the implementation details of a class ```
____
## 13. In Python, self refers to: 
```a) The current class instance ```
____
## 14. Inheritance in Python allows: 
```a) A class to inherit properties and behavior of another class```
____
## 15. Which of the following is true about a constructor in Python?
```d) All of the above```
____
## 16. What is polymorphism in object-oriented programming? 
```a) Ability of a method to do different things based on the object it is acting upon ```
____
## 17. Inheritance in Python allows a subclass to: 
```a) Override methods of the superclass ```
____
## 18. Data abstraction in Python is achieved by: 
```a) Using classes and objects```
____
## 19. In Python, the __init__ function is used for: 
```a) Initializing instance variables of a class ```
____
## 20. In Python, super() is used to: 
```a) Call a method of the parent class ```
____






