# Python-OOP-Assignment

Python OOP Assignment 3

Q1. What is the purpose of Python's OOP?
=>  The purpose of Python's object-oriented programming (OOP) is to provide a programming paradigm that allows for the creation of reusable and modular code through the use of objects and classes.

Q2. Where does an inheritance search look for an attribute?
=>	The whole point of a namespace tool like the class statement is to support name inheritance. In Python, inheritance happens when an 	object is qualified, and involves searching an attribute definition tree (one or more namespaces). Every time you use an expression 	of the form object.

Q3. How do you distinguish between a class object and an instance object?
=>	Object is an instance of a class. Class is a blueprint or template from which objects are created. Object is a real world entity 
	such as pen, laptop, mobile, bed, keyboard, mouse, chair etc. Class is a group of similar objects.

Q4. What makes the first argument in a class’s method function special?
=>	A class method is similar to an instance method, but it has a class object passed as its first argument. Recall that, when an 	instance method is called from an instance object, that instance object is automatically passed as the first argument to the method.
	In Python, special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because 	they start and end with double underscores, for example __init__ 

Q5. What is the purpose of the init method?
=>	When create a new object of a class, Python automatically calls the __init__() method to initialize the object’s attributes.

Q6. What is the process for creating a class instance?
=>  To create instances of a class,  call the class using class name and pass in whatever arguments its __init__ method accepts.

Q7. What is the process for creating a class?
=>	To create a class, use the keyword class : Create a class named ---, with a property named x: Create an object named ---, and 	print the value of x: Create a class named Person, use the __init__() function to assign values for object details: Insert a 	function 	that prints a greeting, and execute it on the object:

Q8. How would you define the superclasses of a class?
=> The class from which a class inherits is called the parent or superclass. A class which inherits from a superclass is called a subclass, also called heir class or child class.

Q9. What is the relationship between classes and modules?
=>  A class is more of a unit, and a module is essentially a loose collection of stuff like functions, variables, or even classes. 

Q10. How do you make instances and classes?
=> Classes: A class is a blueprint or template for creating objects. It defines a set of attributes (data) and behaviors (methods) that the objects created from the class will possess. Think of a class as a blueprint for creating objects of a specific type.

Instances: An instance, also known as an object, is a specific occurrence or realization of a class. It is created based on the blueprint provided by the class. Each instance of a class can have its own unique set of data and can execute methods defined by the class.

Q11. Where and how should be class attributes created?
=>  Class attributes are the variables defined directly in the class that are shared by all objects of the class. Instance attributes are attributes or properties attached to an instance of a class. Instance attributes are defined in the constructor. Defined directly inside a class.

Q12. Where and how are instance attributes created?
=>  Instance attributes are created and defined within the methods of a class, particularly within the special method called the constructor or initializer. In Python, this method is named __init__.

Here's an example of how instance attributes are created and assigned values within the __init__ method:

class MyClass:
    def __init__(self, attribute1, attribute2):
        self.attribute1 = attribute1
        self.attribute2 = attribute2

Q13. What does the term "self" in a Python class mean?
=>   The 'self' keyword refers to the instance of the class being created. By using self.attribute_name, you create an instance attribute and assign it a value

Q14. How does a Python class handle operator overloading?
=>   You can customize the behavior based on your class's logic and requirements. Operator overloading allows you to make your classes more intuitive and work seamlessly with built-in operators.

Q15. When do you consider allowing operator overloading of your classes?
=>  Operator overloading can be considered when you want to provide a more intuitive and natural syntax for working with objects of your class. It can make your code more expressive, readable, and in line with the expected behavior of the operators based on the context of your class.

Q16. What is the most popular form of operator overloading?
=>    
One of the most popular forms of operator overloading is the arithmetic operator overloading, which allows you to define how arithmetic operators (+, -, *, /, etc.) behave when applied to objects of your custom classes.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?
=>   Both inheritance and polymorphism are fundamental concepts of object oriented programming. These concepts help us to create code that can be extended and easily maintainable.

Q18. Describe three applications for exception processing.
=>   Error Handling: Exception processing is primarily used for error handling. When an error or exceptional condition occurs during program execution, an exception is raised, causing the normal flow of the program to be interrupted. 
     
     
  Robustness and Fault Tolerance: Exception processing contributes to building robust and fault-tolerant applications. By anticipating potential exceptions and using approp riate exception handling techniques, you can make your code more resilient to unexpected situations.
    
   Resource Cleanup: Exception processing is commonly used to handle resource cleanup operations. Resources like files, database connections, network sockets, or locks need to be properly released or closed after use to prevent resource leaks and ensure efficient resource management. Exception handling allows you to handle exceptions that may occur during resource operations and ensure that the cleanup code is executed, even if an exception is raised. By using the finally block in combination with try-except, 

Q19. What happens if you don't do something extra to treat an exception?
=>   When an exception occurred, if you don't handle it, the program terminates abruptly and the code past the line that caused the exception will not get executed.

Q20. What are your options for recovering from an exception in your script?
Handling an exception
=>   A single try statement can have multiple except statements. 
You can also provide a generic except clause, which handles any exception.
After the except clause(s), you can include an else-clause. ...
The else-block is a good place for code that does not need the try: block's protection.


Q21. Describe two methods for triggering exceptions in your script.
=>   Try – This method catches the exceptions raised by the program. 
     Raise – Triggers an exception manually using custom exceptions.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of whether or not an exception exists.
=>   Finally Block: The finally block is used in conjunction with the try-except block to specify a set of actions that must be executed regardless of whether an exception is raised or not. The code within the finally block will always be executed, providing a way to ensure that critical cleanup or termination actions are performed.

   Context Managers: Context managers provide a more structured and concise way to specify actions to be executed at termination time. They can be used with the with statement to define a block of code where the necessary setup and teardown actions are automatically taken care of, regardless of exceptions.

      
Q23. What is the purpose of the try statement?
The try statement allows you to define a block of code to be tested for errors while it is being executed. The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

Q24. What are the two most popular try statement variations?
=>  You can have multiple try blocks in a program but only one except statement with each try block. If you want to catch multiple errors, just write.

Q25. What is the purpose of the raise statement?
=>   The raise keyword is used to raise an exception. You can define what kind of error to raise, and the text to print to the user.



Q26. What does the assert statement do, and what other statement is it like?
=>   assert statement takes an expression and optional message. assert statement is used to check types, values of argument and the output of the function. assert statement is used as debugging tool as it halts the program at the point where an error occurs.

Q27. What is the purpose of the with/as argument, and what other statement is it like?
=>   In Python, with statement is used in exception handling to make the code cleaner and much more readable. It simplifies the management of common resources like file streams.


Q28. What are *args, **kwargs?
=> *args specifies the number of non-keyworded arguments that can be passed and the operations that can be performed on the function in Python whereas **kwargs is a variable number of keyworded arguments that can be passed to a function that can perform dictionary operations.

Q29. How can I pass optional or keyword parameters from one function to another?
=>  A type of argument with a default value is a Python optional parameter. A function definition's assignment operator or the Python **kwargs statement can be used to assign an optional argument.

Q30. What are Lambda Functions?
=>   A lambda function is a small anonymous function. A lambda function can take any number of arguments, but can only have one expression.

Q31. Explain Inheritance in Python with an example?
=>   Inheritance relationship defines the classes that inherit from other classes as derived, subclass, or sub-type classes. Base class remains to be the source from which a subclass inherits. For example, you have a Base class of “Animal,” and a “Lion” is a Derived class. The inheritance will be Lion is an Animal.

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked?
=>    if class C inherits from classes A and B, and both classes A and B have their own versions of the method func(), the method resolution order (MRO) determines which version of func() will be invoked when called from an object of class C.  
 

Q33. Which methods/functions do we use to determine the type of instance and inheritance?
=>   Using isinstance() function, we can test whether an object/variable is an instance of the specified type or class such as int or list. In the case of inheritance, we can checks if the specified class is the parent class of an object.

Q34.Explain the use of the 'nonlocal' keyword in Python.
=>   The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function. Use the keyword nonlocal to declare that the variable is not local.


Q35. What is the global keyword?
=> Global variables are defined outside of all the functions, usually on top of the program. The global variables will hold their value throughout the lifetime of your program. A global variable can be accessed by any function.
