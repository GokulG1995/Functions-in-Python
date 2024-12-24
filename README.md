# Functions-in-Python
Functions in Python, Functions in Python are blocks of code that perform a specific task and can be reused throughout the program. They help in organizing code, avoiding repetition, and improving readability.
1. Defining a Function:
Functions are defined using the def keyword, followed by the function name and parentheses.



def greet():
    print("Hello, World!")
2. Calling a Function:
After defining a function, it can be called by using its name followed by parentheses.



greet()  # Output: Hello, World!
3. Functions with Arguments:
Functions can accept input values, known as parameters or arguments, to perform operations on them.



def greet(name):
    print(f"Hello, {name}!")

greet("Alice")  # Output: Hello, Alice!
4. Return Statement:
A function can return a value using the return statement. This allows the function to produce output that can be used elsewhere in the program.



def add(a, b):
    return a + b

result = add(3, 4)
print(result)  # Output: 7
5. Default Arguments:
Functions can have default values for parameters, which are used when no value is passed.



def greet(name="Guest"):
    print(f"Hello, {name}!")

greet()      # Output: Hello, Guest!
greet("Bob") # Output: Hello, Bob!
6. Variable-Length Arguments:
Functions can accept a variable number of arguments using *args (for non-keyword arguments) or **kwargs (for keyword arguments).

*args: Used to pass a variable number of non-keyword arguments.



def sum_numbers(*args):
    return sum(args)

print(sum_numbers(1, 2, 3, 4))  # Output: 10
**kwargs: Used to pass a variable number of keyword arguments.



def show_details(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")

show_details(name="Alice", age=25)
7. Lambda Functions:
A lambda function is a small anonymous function defined using the lambda keyword. It can have any number of arguments but only one expression.



add = lambda x, y: x + y
print(add(2, 3))  # Output: 5
Functions are essential in Python for breaking down complex problems into smaller, manageable pieces of code.
