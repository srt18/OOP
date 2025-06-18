## OOP 
- Object-oriented programming paradigm
- Uses the concept of objects whihc refuse the real-world entities with state & behaviour

### Principles of OOPs concept
 - Class
 - Object
 - Encapsulation
 - Inheritance
 - Polymorphism
   
### Class
   - A class is a blueprint or template for creating objects. 
   - It defines the properties and methods that an object of that class will have. 
   - Properties are the data or state of an object, and methods are the actions or   behaviors that an object can perform.

### Object
   - An object is an instance of a class, and it contains its own data and methods. 
  - For example, you could create a class called "Person" that has properties such as name and age, and methods such as speak() and walk().
    Each instance of the Person class would be a unique object with its own name and age, but they would all have the same methods to speak and walk.

#### Self
   - Self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class.

   - It used to provided as the extra parameter inside the method definition.

### Encapsulation
   - One of the kay features of OOP in Python is encapsulation, which means that the internal state of an object is hidden and can only be accessed or modified through the object's methods. 
   - This helps to protect the object's data and prevent it from being modified in unexpected ways.

### Inheritance
   - Another key feature of OOP in Python is inheritance, which allows new classes to be created that inherit the properties and methods of an existing class.
   -  This allows for code reuse and makes it easy to create new classes that have similar functionality to existing classes.

### Polymorphism
   - Polymorphism is also supported in Python, which means that objects of different classes can be treated as if they were objects of a common class. 
   - This allows for greater flexibility in code and makes it easier to write code that can work with multiple types of objects.

In summary, OOP in Python allows developers to model real-world concepts and entities using classes and objects, encapsulate data, reuse code through inheritance, and write more flexible code through polymorphism.


#### Constructor (dunker Method or magic method)

   - A constructor is a special method in a class used to create and initialize an object of a class. 
   - There are different types of constructors. Constructor is invoked automatically when an object of a class is created. 
   -   A constructor is a unique function that gets called automatically when an object is created of a class. 
   -   The main purpose of a constructor is to Initialize or assign values to the data members of that class. It cannot return any value other than None.
   - __init__ is one of the reserved functions in Python. In Object Oriented Programming, it is known as a constructor. We can also create constructor by defining the function name with same class name.
   - Default Constructor In Python : When the constructor doesn't accept any arguments from the object and has only one argument, self, in the constructor, it is known as a Default constructor.

#### Decorator 
   -  Why to use decorator?
   - Python decorators are a powerful and versatile tool that allow you to modify the behavior of functions and methods. 
   - They are a way to extend the functionality of a function or method without modifying its source code.
   - A decorator is a function that takes another function as an argument and returns a new function that modifies the behavior of the original function. 
   - The new function is often referred to as a "decorated" function. 
   - Practical use case --> logging memoization and access control.
    
