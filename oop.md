Object Oriented Programming in JavaScript
Last Updated : 14 Jan, 2026
Object Oriented Programming (OOP) is a style of programming that uses classes and objects to model real-world things like data and behavior. A class is a blueprint that defines the properties and methods an object can have, while an object is a specific instance created from that class.

Why OOP is Needed:

Before OOP, when the code size grows and multiple people work on a project, there problems arise

Changing in one team's code causing other codes to break. Hence difficult to maintain.
Large number of parameters during function calls.
Difficult to divide and maintain code across teams.
Limited Code Reusability
Not scalable as the code is not modular.
Object Oriented Programming (OOP) solves these problems by combining data and the functions that operate on it into a single unit called an object. This approach has following main features

Encapsulation ensures that one team can change data representation and algorithms without causing other team's code change.
Inheritance ensures code reuse.
Polymorphism allows objects to behave differently using the same interface.


Types-of-OOPS-2
Objects
In JavaScript, an object is a collection of data (properties) and actions (methods) stored as key–value pairs.

Properties hold values like strings, numbers, or even other objects.
Methods are functions inside the object that define what it can do.
Objects let you group related data and functionality together in one place.

Classes
In JavaScript, a class is a blueprint for creating objects with specific properties and methods. A class itself doesn’t hold values, it describes what an object should have and do. You create actual objects from a class using the new keyword.

Example:



// Class definition
class Car {
  constructor(brand, model) {
    this.brand = brand; // property
    this.model = model; // property
  }
​
  // method
  showDetails() {
    console.log(`This car is a ${this.brand} ${this.model}.`);
  }
}
​
// Creating objects from the class
const car1 = new Car("Toyota", "Corolla");
const car2 = new Car("Honda", "Civic");
​
// Using the objects
car1.showDetails(); // This car is a Toyota Corolla.
car2.showDetails(); // This car is a Honda Civic.
Output:

This car is a Toyota Corolla.
This car is a Honda Civic.