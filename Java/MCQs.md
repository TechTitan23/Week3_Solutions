
____
## 6. How do you access the members (variables and methods) of a structure (class)?

``` b. Using the dot operator (.).```
____
## 7. What is the purpose of a structure (class) in Java?
``` a. To represent a group of related data members and methods. ```
____
## 8. Can function overloading be based solely on the return type in Java?
``` b. No, it is not allowed in Java.```
____
## 9. Which keyword is used to define a function?
```Method```
____
## 10. What is the primary purpose of a function in Java?
```b. To organize code into reusable blocks.```
____
## 11. Guess the Output:
public class MyClass {
    public MyClass() {
        System.out.println("Inside the constructor");
    }

    public static void main(String[] args) {
        MyClass obj = new MyClass();
    }
}
### Output :
```Inside the constructor```
____
## 12. Guess the Output:
public class MyClass {
    private int number;

    public MyClass(int num) {
        this.number = num;
    }

    public int getNumber() {
        return this.number;
    }

    public static void main(String[] args) {
        MyClass obj = new MyClass(50);
        System.out.println("Number: " + obj.getNumber());
    }
}

### Output :
```Number: 50```
____
## 13 . What is the output of the following Java code snippet?
class MyClass {
    int x = 10;
    void printValue() {
        System.out.println(x);
    }
}
public class Main {
    public static void main(String[] args) {
        MyClass obj1 = new MyClass();
        MyClass obj2 = new MyClass();
        obj1.x = 5;
        obj1.printValue();
        obj2.printValue();
    }
}
### Output
```5```
____
## 14.What is the output of the following Java code snippet?
class Vehicle {
    void start() {
        System.out.println("Vehicle started.");
    }
}
class Car extends Vehicle {
    void start() {
        System.out.println("Car started.");
    }
}
public class Main {
    public static void main(String[] args) {
        Vehicle myVehicle = new Car();
        myVehicle.start();
    }
}
### Output
```Car started```
____
## 15.What is the primary purpose of a constructor in a Java class?
```b. To initialize instance variables of the class```




