# JavaSE-Classes

See the Udemy course: https://www.udemy.com/course/curso-certificacion-profesional-desarrollador-java-se-11

## Classes
In Java, a class is a blueprint for creating objects. Objects are instances of classes, and they encapsulate data (attributes) and behaviors (methods). Let me show you a simple example:

```java
// Define a class called 'Car'
public class Car {
    // Declare some attributes (fields)
    String brand;
    String model;
    int year;

    // Constructor - a special method to initialize objects
    public Car(String brand, String model, int year) {
        this.brand = brand;
        this.model = model;
        this.year = year;
    }

    // Method to display information about the car
    public void displayInfo() {
        System.out.println("Brand: " + brand);
        System.out.println("Model: " + model);
        System.out.println("Year: " + year);
    }

    // Method to start the car
    public void start() {
        System.out.println("The car is starting...");
    }
}

// Main class to test our 'Car' class
public class Main {
    public static void main(String[] args) {
        // Create an instance of the Car class
        Car myCar = new Car("Toyota", "Camry", 2021);

        // Accessing attributes and calling methods
        myCar.displayInfo();
        myCar.start();
    }
}
```

Let me break it down:

We define a class called Car with attributes (brand, model, year) and methods (displayInfo and start).

We create a constructor (public Car) to initialize the object when it's created.

In the Main class, we create an instance of the Car class called myCar and initialize it with specific values.

We then call methods and access attributes of the myCar object.

This is a basic example, but classes in Java can get much more complex with features like inheritance, polymorphism, and encapsulation.
