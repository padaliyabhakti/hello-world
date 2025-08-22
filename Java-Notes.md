# Java Notes: Classes, Objects, and Inheritance

## 1. Classes and Objects
- **Class**: Blueprint for creating objects; defines properties (variables) and methods (functions).  
- **Object**: Instance of a class; it holds actual values.  

**Example:**
```java
class Car {
    String color;
    int speed;

    void display() {
        System.out.println("Color: " + color + ", Speed: " + speed);
    }
}

public class Main {
    public static void main(String[] args) {
        Car myCar = new Car(); // Creating an object
        myCar.color = "Red";
        myCar.speed = 100;
        myCar.display();
    }
}
