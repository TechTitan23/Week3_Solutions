
____
## 6. How do you access the members (variables and methods) of a structure (class)?

``` b. Using the dot operator (.).```
____
## 7. What is the purpose of a structure (class) in C++?
``` a. To represent a group of related data members and methods. ```
____
## 8. Can function overloading be based solely on the return type in C++?
``` b. No, it is not allowed in Java.```
____
## 9. Which keyword is used to define a function?
```Functions```
____
## 10. What is the primary purpose of a function in C++?
```b. To organize code into reusable blocks.```
____
## 11. Guess the Output:
#include <iostream>
using namespace std;

class MyClass {
public:
    MyClass() {
        cout << "Inside the constructor" << endl;
    }
};

int main() {
    MyClass obj;
    return 0;
}

### Output :
```Inside the constructor```
____
## 12. Guess the Output:
#include <iostream>
using namespace std;

class MyClass {
private:
    int number;
public:
    MyClass(int num) : number(num) {}
    int getNumber() {
        return number;
    }
};

int main() {
    MyClass obj(50);
    cout << "Number: " << obj.getNumber() << endl;
    return 0;
}


### Output :
```Number: 50```
____
## 13 . What is the output of the following C++ code snippet?
#include <iostream>
using namespace std;

class MyClass {
public:
    int x = 10;

    void printValue() {
        cout << x << endl;
    }
};

int main() {
    MyClass obj1;
    MyClass obj2;
    obj1.x = 5;
    obj1.printValue();
    obj2.printValue();
    return 0;
}

### Output
```5```
____
## 14.What is the output of the following C++ code snippet?
#include <iostream>
using namespace std;

class Vehicle {
public:
    void start() {
        cout << "Vehicle started." << endl;
    }
};

class Car : public Vehicle {
public:
    void start() {
        cout << "Car started." <<endl;
    }
};

int main() {
    Vehicle myVehicle = Car();
    myVehicle.start();
    return 0;
}

### Output
```Car started```
____
## 15.What is the primary purpose of a constructor in a C++ class?
```b. To initialize instance variables of the class```
