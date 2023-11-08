# Functions

- Functions are standalone blocks of code that can be defined at the module level (outside of classes) or within other - functions.
- They can be called and executed independently, without any specific object or instance.
- Functions are defined using the def keyword followed by a function name, a parameter list (if any), and a code block.
## Example of a function:

python Copy code
```
def add(a, b):
    return a + b

    
Methods:
Methods, on the other hand, are functions that are associated with objects or instances of a class. They are defined within a class and are used to perform operations specific to that class.
Methods are called on instances of a class and often operate on the data or attributes of the instance.
Methods are defined within a class using the def keyword, just like functions, but they have an additional first parameter commonly named self, which refers to the instance on which the method is called.
Example of a method within a class:

python
Copy code
class Calculator:
    def __init__(self):
        self.result = 0

    def add(self, a, b):
        self.result = a + b

calc = Calculator()
calc.add(3, 4)
print(calc.result)  # Outputs 7
In summary, the main difference between methods and functions in Python is that methods are associated with classes and operate on instances of those classes, while functions are standalone blocks of code that can be used independently. Methods have an additional self parameter, and they are defined within classes, whereas functions are defined at the module level.