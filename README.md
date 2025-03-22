<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AN OVERVIEW OF BASICS PYTHON CONCEPTS</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/monokai-sublime.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1><marquee behaviour="scroll" direction="left">AN OVERVIEW OF BASIC PYTHON CONCEPTS</marquee></h1>
            <nav>
                <ul class="main-nav">
                    <li><a href="#introduction">Introduction</a></li>
                    <li><a href="#datatypes">Datatypes</a></li>
                    <li><a href="#operators">Operators</a></li>
                    <li><a href="#conditional-statements">Conditional Statements</a></li>
                    <li><a href="#looping-statements">Looping Statements</a></li>
                    <li><a href="#nested-loop">Nested Loop</a></li>
                    <li><a href="#functions">Functions</a></li>
                    <li><a href="#class-objects">Class and Objects</a></li>
                    <li><a href="#exception-handling">Exception Handling</a></li>
                    <li><a href="#construction-destruction">Construction & Destruction</a></li>
                    <li><a href="#python-mysql">Python with MySQL</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <script>
        window.alert("Welcome to my Website!");
        window.alert("IMPORTANT NOTICE!: Please note that while I developed it, the basic structure and many elements were created with the assistance of resources like Gemini, Youtube tutorials, Github examples, W3Schools documentation and etc.");
    </script>

    <main>
        <div class="container">
            <section id="introduction" class="topic-section">
                <h2>Introduction to Python</h2>
                <ul>
                    <li>Python is a high-level, interpreted, general-purpose programming language.</li>
                    <li>It is a popular programming language.</li>
                    <li>It can be used on a server to create web applications.</li>
                    <li>It was created by Guido Van Rossum and released in 1991.</li>
                    <li>Its design philosophy emphasizes code readability with the use of significant indentation.</li>
                    <li>Python is dynamically-typed and garbage-collected.</li>
                    <li>It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.</li>
                    <li>It has a simple syntax similar to the English Language.</li>
                    <h3>Code Example:</h3>
                    <pre><code class="language-python">
print("Hello World") #Output:Hello World
                    </code></pre>
                </ul>
                <h3>Key Features:</h3>
                <ul>
                    <li>Easy to learn and use: Python's syntax is clear and concise, making it beginner-friendly.</li>
                    <li>Extensive standard library: Python comes with a vast library of modules and functions, reducing development time.</li>
                    <li>Large community support: A vibrant community contributes to Python's growth, providing resources and support.</li>
                    <li>Versatile and can be used for various applications: From web development to data science and AI, Python is highly adaptable.</li>
                    <li>It is used for:<br>
                        * Web development (Server-Side)<br>
                        * Software development<br>
                        * Mathematics<br>
                        * System scripting<br>
                    </li>
                </ul>
                <h3>Variables:</h3>
                <ul>
                    <li>In Python, variables are created when you assign a value to it.</li>
                    <li>Variables are containers for storing data values.</li>
                    <h3>Code Example:</h3>
                    <pre><code class="language-python">
x = str(3)
y = int(3)
z = float(3)
print(x, y, z) #Output:3 3 3.0
print(type(x)) #Output:class 'str'
print(type(y)) #Output:class 'int'
print(type(z)) #Output:class 'float'
                    </code></pre>
                </ul>
                <h3>Comments:</h3>
                <ul>
                    <li>It starts with a #, and Python will ignore them.</li>
                    <li>It starts with """,ends with """ and Python will ignore them.</li>
                    <h3>Code Example:</h3>
                    <pre><code class="language-python">
#This is single line comment
"""This is the 
multi line
comment"""
                    </code></pre>
                </ul>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://www.python.org/" target="_blank">Official Python Website</a></li>
                    <li><a href="https://docs.python.org/3/" target="_blank">Python Documentation</a></li>
                    <li><a href="https://realpython.com/" target="_blank">Real Python Tutorials</a></li>
                    <li><a href="https://www.codecademy.com/learn/learn-python-3" target="_blank">Codecademy Python 3 Course</a></li>
                    <li><a href="https://www.w3schools.com/python/python_variables.asp" target="_blank">W3schools python tutorial for variables</a></li>
                    <li><a href="https://www.w3schools.com/python/python_comments.asp" target="_blank">W3schools python tutorial for comments</a></li>
                </ul>
            </section>

            <section id="datatypes" class="topic-section">
                <h2>Datatypes in Python</h2>
                <p>Datatypes represent the type of value that a variable holds. Python has several built-in datatypes:</p>
                <ul>
                    <li><strong>Numbers:</strong> Integers (e.g., 10), Floats (e.g., 3.14), Complex numbers (e.g., 3+5j). Python supports arbitrary-precision integers.</li>
                    <li><strong>String:</strong> Ordered sequence of characters (e.g., "Hello"). Strings are immutable in Python.</li>
                    <li><strong>List:</strong> Ordered and mutable sequence of items (e.g., [1, 2, 3]). Lists can contain items of different datatypes.</li>
                    <li><strong>Tuple:</strong> Ordered and immutable sequence of items (e.g., (1, 2, 3)). Tuples are often used for data that shouldn't be changed.</li>
                    <li><strong>Set:</strong> Unordered collection of unique items (e.g., {1, 2, 3}). Sets are useful for operations like union, intersection, and difference.</li>
                    <li><strong>Dictionary:</strong> Unordered collection of key-value pairs (e.g., {'a': 1, 'b': 2}). Dictionaries are highly efficient for looking up values by key.</li>
                    <li><strong>Boolean:</strong> Represents truth values (True or False). Booleans are essential for control flow.</li>
                    <li><strong>NoneType:</strong> Represents the absence of a value.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
x = 10
y = 3.14
name = "Python"
my_list = [1, 2, 3]
my_tuple = (4, 5, 6)
my_set = {7, 8, 9}
my_dict = {'key': 'value'}
is_valid = True
none_value = None

print("Type of x: " , type(x)) #Output:Type of x: class 'int'
print("Type of y: " , type(y)) #Output:Type of x: class 'float'
print("Type of name: " ,  type(name)) #Output:Type of x: class 'str'
print("Type of my_list: " ,  type(my_list)) #Output:Type of x: class 'list'
print("Type of my_tuple: " ,  type(my_tuple)) #Output:Type of x: class 'tuple'
print("Type of my_set: " ,  type(my_set)) #Output:Type of x: class 'set'
print("Type of my_dict: " ,  type(my_dict)) #Output:Type of x: class 'dict'
print("Type of is_valid: " ,  type(is_valid)) #Output:Type of x: class 'bool'
print("Type of none_value: " ,  type(none_value)) #Output:Type of x: class 'NoneType'

list_example = [1, "hello", 3.14]
print("Example list: " ,  list_example) #Output:Example list: [1, 'hello', 3.14]

tuple_example = (10, 20, 30)
print("Example tuple: " ,  tuple_example) #Output:Example tuple: (10, 20, 30)

dict_example = {"name": "Alice", "age": 30}
print("Example dictionary: " ,  dict_example) #Output:Example dictionary: {'name': 'Alice', 'age': 30}
                </code></pre>
                <h3>Slicing strings:</h3>
                <ul>
                    <li>Slicing strings in Python allows you to extract portions of a string by specifying a range of indices.</li>
                    <li>It's a powerful and flexible technique.</li>
                </ul>
                <h3>Syntax:</h3>
                <pre><code class="language-python">
string[start:stop:step]
                </code></pre>
                <ul>
                    <li>start: The index where the slice begins (inclusive). If omitted, it defaults to 0 (the beginning of the string).</li>
                    <li>stop: The index where the slice ends (exclusive). If omitted, it defaults to the length of the string (the end of the string).</li>
                    <li>step: The increment between indices. If omitted, it defaults to 1.</li>
                </ul>
                <h3>Code Example 1:</h3>
                <pre><code class="language-python">
text = "Python Programming"

substring1 = text[0:6]  # or text[:6] (start defaults to 0)
print(substring1)  # Output: Python

substring2 = text[7:len(text)]  # or text[7:] (stop defaults to end)
print(substring2)  # Output: Programming

substring3 = text[7:14]
print(substring3) # Output: Program
                </code></pre>
                <h3>Code Example 2:</h3>
                <pre><code class="language-python">
text = "0123456789"

# Extract every other character
substring4 = text[0:10:2]  # or text[::2]
print(substring4)  # Output: 02468

# Extract every third character
substring5 = text[::3]
print(substring5) # Output: 0369
                </code></pre>
                <h3>Code Example 3:</h3>
                <pre><code class="language-python">
text = "Hello World"

# Extract the last 5 characters
substring6 = text[-5:]
print(substring6)  # Output: World

# Extract characters from the 3rd last to the 2nd character.
substring7 = text[-3:-1]
print(substring7) # Output: rl

text2 = "Python"

reversed_text = text2[::-1]
print(reversed_text)  # Output: nohtyP
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://docs.python.org/3/library/stdtypes.html" target="_blank">Python Standard Types</a></li>
                    <li><a href="https://www.w3schools.com/python/python_datatypes.asp" target="_blank">W3Schools Python Datatypes</a></li>
                    <li><a href="https://realpython.com/python-data-types/" target="_blank">Real Python Data Types in Python</a></li>
                    <li><a href="https://www.w3schools.com/python/python_strings_slicing.asp" target="_blank">Python slicing strings</a></li>
                </ul>
            </section>

            <section id="operators" class="topic-section">
                <h2>Operators in Python</h2>
                <p>Operators are symbols that perform operations on operands. Python supports various types of operators:</p>
                <ul>
                    <li><strong>Arithmetic Operators:</strong> +, -, *, /, %, **, //. Python's division operator (/) always returns a float.</li>
                    <li><strong>Comparison Operators:</strong> ==, !=, >, <, >=, <=. These operators return boolean values.</li>
                    <li><strong>Logical Operators:</strong> and, or, not. Used to combine or negate boolean expressions.</li>
                    <li><strong>Assignment Operators:</strong> =, +=, -=, *=, /=, etc. Shorthand for assigning values to variables.</li>
                    <li><strong>Membership Operators:</strong> in, not in. Check if a value is present in a sequence.</li>
                    <li><strong>Identity Operators:</strong> is, is not. Check if two variables refer to the same object in memory.</li>
                    <li><strong>Bitwise Operators:</strong> &, |, ^, ~, <<, >>. Operate on individual bits of integers.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
a = 10
b = 5

print("Addition: " ,  a + b)
print("Subtraction: " ,  a - b)
print("Multiplication: " ,  a * b)
print("Division: " ,  a / b)
print("Modulus: " ,  a % b)
print("Exponentiation: " ,  a ** b)
print("Floor Division: " ,  a // b)

print("a == b: " ,  a == b)
print("a > b: " ,  a > b)

x = True
y = False
print("x and y: " ,  x and y)
print("x or y: " ,  x or y)
print("not x: " ,  not x)

my_list = [1, 2, 3]
print("2 in my_list: " ,  2 in my_list)

list1 = [1, 2, 3]
list2 = list1
list3 = [1, 2, 3]
print("list1 is list2: " ,  list1 is list2)
print("list3 is list3: " ,  list1 is list3) # False because they are different objects

a = 10
a += 5
print("a += 5 : " ,  a)

print("Bitwise AND (10 & 4): " ,  10 & 4)

a=10
b=20
a=a^b
b=a^b
a=a^b
print("a=",a)
print("b=",b)

#Output:
Addition:  15
Subtraction:  5
Multiplication:  50
Division:  2.0
Modulus:  0
Exponentiation:  100000
Floor Division:  2
a == b:  False
a > b:  True
x and y:  False
x or y:  True
not x:  False
2 in my_list:  True
list1 is list2:  True
list3 is list3:  False
a += 5 :  15
Bitwise AND (10 & 4):  0
a= 20
b= 10
                    
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://docs.python.org/3/library/operator.html" target="_blank">Python Operator Module</a></li>
                    <li><a href="https://www.tutorialspoint.com/python/python_operators.htm" target="_blank">TutorialsPoint Python Operators</a></li>
                    <li><a href="https://realpython.com/python-operators/" target="_blank">Real Python Python Operators and Expressions</a></li>
                </ul>
            </section>

            <section id="conditional-statements" class="topic-section">
                <h2>Conditional Statements in Python</h2>
                <ul>
                    <li>Conditional statements allow you to execute different blocks of code based on whether a condition is true or false.</li>
                    <li>Python uses <code>if</code>, <code>elif</code> (else if), and <code>else</code> for conditional logic.</li>
                    <li>Indentation is crucial in Python to define code blocks.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
age = 20
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
#Output: You are an adult.

score = 75
if score >= 90:
    print("Excellent!")
elif score >= 70:
    print("Good.")
elif score >= 60:
    print("Average.")
else:
    print("Needs improvement.")
#Output: Good.

number = 0
if number > 0:
    print("Positive")
elif number < 0:
    print("Negative")
else:
    print("Zero")
#Output: Zero

is_raining = True
if is_raining:
    print("Take an umbrella")
else:
    print("Enjoy the sunshine")
#Output: Take an umbrella
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://docs.python.org/3/tutorial/controlflow.html#if-statements" target="_blank">Python if Statements</a></li>
                    <li><a href="https://www.programiz.com/python-programming/if-elif-else" target="_blank">Programiz Python if...elif...else</a></li>
                    <li><a href="https://www.geeksforgeeks.org/python-if-else/" target="_blank">GeeksforGeeks Python If Else</a></li>
                </ul>
            </section>

            <section id="looping-statements" class="topic-section">
                <h2>Looping Statements in Python</h2>
                <ul>
                    <li>Looping statements allow you to repeatedly execute a block of code.</li>
                    <li>Python provides <code>for</code> and <code>while</code> loops.</li>
                    <li>The <code>for</code> loop is often used to iterate over sequences, while the <code>while</code> loop continues as long as a condition is true.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
for i in range(5):
    print(i)
#Output:
0
1
2
3
4

my_list = ["apple", "banana", "cherry"]
for item in my_list:
    print(item)
#Output:
apple
banana
cherry

count = 0
while count < 5:
    print(count)
    count += 1
#Output:
0
1
2
3
4

numbers = [1,2,3,4,5]
for number in numbers:
  print(number * 2)
#Output:
2
4
6
8
10

i = 1
while i <= 5:
  print(i)
  i +=1
#Output:
1
2
3
4
5
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://www.w3schools.com/python/python_for_loops.asp" target="_blank">Python for loop</a></li>
                    <li><a href="https://docs.python.org/3/tutorial/controlflow.html#for-statements" target="_blank">Python for Statements</a></li>
                    <li><a href="https://docs.python.org/3/tutorial/controlflow.html#while-statements" target="_blank">Python while Statements</a></li>
                    <li><a href="https://www.geeksforgeeks.org/python-loops/" target="_blank">GeeksforGeeks Python Loops</a></li>
                </ul>
            </section>

            <section id="nested-loop" class="topic-section">
                <h2>Nested Loops in Python</h2>
                <ul>
                    <li>A nested loop is a loop inside another loop.</li>
                    <li>This is useful for iterating over multiple dimensions of data or performing operations that require multiple levels of iteration, such as processing elements in a 2D array or generating combinations.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
for i in range(0,5):
    for j in range(0,5):
        print("*",end=" ")
    print(" ")
#Output:
* * * * *  
* * * * *  
* * * * *  
* * * * *  
* * * * * 

for i in range(0,5):
    for j in range(0,i):
        print("*",end="")
    print()
#Output:
*
**
***
****

for i in range(5,0,-1):
    for j in range(0,i):
        print("*",end="")
    print()
#Output:
*****
****
***
**
*

matrix = [[1,2,3],[4,5,6],[7,8,9]]
for row in matrix:
    for element in row:
        print(element,end=" ")
    print()
#Output:
1 2 3 
4 5 6 
7 8 9 

for i in range(1,4):
    for j in range(1,4):
        print(i*j,end=" ")
    print()
#Output:
1 2 3 
2 4 6
3 6 9
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://www.w3schools.com/python/python_for_loops.asp" target="__blank">Python for loop</a></li>
                    <li><a href="https://www.tutorialspoint.com/python/nested_loops_in_python.htm" target="_blank">TutorialsPoint Nested Loops in Python</a></li>
                    <li><a href="https://www.geeksforgeeks.org/nested-loops-in-python/" target="_blank">GeeksforGeeks Nested Loops in Python</a></li>
                </ul>
            </section>

            <section id="functions" class="topic-section">
                <h2>Functions in Python</h2>
                <ul>
                    <li>Functions are blocks of reusable code that perform a specific task.</li>
                    <li>They help in organizing code, making it more readable and maintainable.</li>
                    <li>Python supports defining functions with parameters and return values.</li>
                    <li>You can also define default parameter values and use keyword arguments.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
#Local variable
def num():
    k=80
    print(k) #Output: 80
num()

#Enclosing variable
def num():
    k=80
    def nums():
        print(k) #Output: 80
    nums()
num()

#Global variable
k=80
def num():
    print(k) #Output: 80
num()

#Built-In variable
from math import *
def num():
    k=80
    def nums():
        print(k) #Output: 80
    nums()
num()

                </code></pre>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
#Without argument without return type
def sayhello():
    print("Hello") #Output: Hello
sayhello()

#Without argument with return type
def sum():
    a,b=10,20
    return a+b
k=sum()
print(k) #Output: 30

#With argument with return type
def sum(a,b):
    print(a+b) #Output: 30
sum(10,20)

#With argument with return type
def sum(a,b):
    return a+b
k=sum(10,20)
print(k) #Output: 30
                </code></pre>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
#Recursive function: A function is called repetitively by itself. A recursive can be used directly or indirectly.
def fac(n):
    if n==1:
        return 1
    else:
        return n*fac(n-1)
n=int(input("enter n:"))
k=fac(n)
print(k) #Output: enter n:5 120

def power(n,i):
    if i==1:
        return n
    else:
        return n*power(n,i-1)
n=int(input("enter n:"))
i=int(input("enter i:"))
k=power(n,i)
print(k)

#Output:
enter n:3
enter i:4
81
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://docs.python.org/3/tutorial/functions.html" target="_blank">Python Defining Functions</a></li>
                    <li><a href="https://www.w3schools.com/python/python_functions.asp" target="_blank">W3Schools Python Functions</a></li>
                    <li><a href="https://realpython.com/defining-your-own-python-functions/" target="_blank">Real Python Defining Your Own Python Functions</a></li>
                </ul>
            </section>

            <section id="class-objects" class="topic-section">
                <h2>Classes and Objects in Python</h2>
                <ul>
                    <li>Python is an object-oriented programming (OOP) language.</li>
                    <li>Classes are blueprints for creating objects, and objects are instances of classes.</li>
                    <li>OOP helps in modeling real-world entities and organizing code effectively.</li>
                    <li>Key concepts include encapsulation, abstraction, inheritance, and polymorphism.</li>
                </ul>
                <ul>
                    <h3>1, Inheritance:</h3>
                    <li>It allows us to define a class that inherits all the methods and properties from another class.</li>
                    <li>Inheritance is a powerful tool for designing and organizing object-oriented programs.</li>
                    <li>It allows you to create more modular, reusable, and maintainable code.</li>
                    <li>Types of Inheritance:</li>
                        <p>a, Single Inheritance</p>
                        <p>b, Multilevel Inheritance</p>
                        <p>c, Multiple Inheritance</p>
                        <p>d, Hierachical Inheritance</p>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
#Single Inheritance

class Flower:
    def smell(self):
        print("Flower")

class Rose(Flower):
    def smel(self):
        print("Rose")

rr = Rose()
rr.smell()
rr.smel() #Output: Flower Rose

#Multilevel Inheritance

class Flower:
    def smell(self):
        print("Flower")

class Rose(Flower):
    def smel(self):
        print("Rose")

class Lily(Rose):  
    def sme(self):
        print("Lily")

l = Lily()

l.smell()
l.smel()
l.sme() #Output: Flower Rose Lily

#Multiple Inheritance

class Rose:
    def smell(self):
        print("Rose")

class Lily:
    def smel(self):
        print("Lily")

class Flower(Rose, Lily):
    def sme(self):
        print("Flower")

f = Flower()

f.smell()
f.smel()
f.sme() #Output: Rose Lily Flower

#Hierachical Inheritance

class Flower:
    def smell(self):
        print("Flower")

class Rose(Flower):
    def smel(self):
        print("Rose")

class Lily(Flower):
    def sme(self):
        print("lily")

r = Lily()
rr = Rose()

rr.smell()
rr.smel()
r.sme() #Output: Flower Rose lily
                </code></pre>
                <ul>
                    <h3>2, Polymorphism:</h3>
                    <li>Polymorphism is a fundamental concept in object-oriented programming (OOP) that allows objects of different classes to respond to the same method call in a way that is specific to their type.</li>
                    <li>In essence, it means "many forms."</li>
                    <li> It promotes code flexibility and extensibility by allowing you to add new classes that can work with existing code without modifying it.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
class Animal:
    def sound(self):
        print("Animal")

class Dog(Animal):
    def sound(self):
        print("Bow")

class Cat(Animal):
    def sound(self):
        print("Meow")

a = Animal()
b = Dog()
c = Cat()

for i in (a,b,c):
    i.sound() #Output:Animal Bow Meow
                </code></pre>
                <h3>3, Abstraction:</h3>
                <ul>
                    <li>It refers to the process of creating abstract classes and methods that provide a blueprint for other classes to inherit form.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
from abc import ABC, abstractmethod

class Power(ABC):
    @abstractmethod
    def energy(self):
        pass

class Engine(Power):
    def energy(self):
        print("Engine")

class Motor(Power):
    def energy(self):
        print("Motor")

a=Engine()
b=Motor()

for i in (a,b):
    i.energy() #Output: Engine Motor
                </code></pre>
                <h3>4, Encapsulation:</h3>
                <ul>
                    <li>Encapsulation is one of the four fundamental principles of object-oriented programming (OOP).</li>
                    <li>It involves bundling data (attributes) and methods (functions) that operate on the data into a single unit, known as a class.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
class base:
    def __init__(self):
        self.a=2
class derived(base):
    def __init__(self):
        base. __init__(self)
        print(self.a)
        self.a=3
        print(self.a)
o1=derived()
o2=base()
print(o1.a)
print(o2.a) #Output: 2 3 3 2
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://docs.python.org/3/tutorial/classes.html" target="_blank">Python Classes</a></li>
                    <li><a href="https://realpython.com/python3-object-oriented-programming/" target="_blank">Real Python OOP in Python</a></li>
                    <li><a href="https://www.geeksforgeeks.org/python-oops-concepts/" target="_blank">GeeksforGeeks Python OOPs Concepts</a></li>
                </ul>
            </section>

            <section id="exception-handling" class="topic-section">
                <h2>Exception Handling in Python</h2>
                <ul>
                    <li>When an error occurs or exceptional as we call it, Python will stop and generate an error message.</li>
                    <li>Exception handling is the process of responding to unwanted or unexpected events that occur when a program is running.</li>
                    <li>Python uses <code>try</code>, <code>except</code>, <code>else</code>, and <code>finally</code> blocks to handle exceptions.</li>
                    <br>
                    <p>Try:</p>
                    <li>The try block lets you test a block of code for errors.</li>
                    <p>Except:</p>
                    <li>The except block lets you handle the error.</li>
                    <p>Finally:</p>
                    <li>The finally block lets you execute code, regardless of the result of the try and except blocks.</li>
                    <p>Else:</p>
                    <li>The else block lets you execute code when there is no error.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
try:
    print(x)
except:
    print("An Exception occured!") #Output: An Exception occured!

try:
    print(5)
except:
    print("An Exception occured!")
else:
    print("No error!") #Output: 5 No error!

try:
    a=[1,2]
    print(a[2])
except:
    print("An Exception occured!")
finally:
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://docs.python.org/3/tutorial/errors.html" target="_blank">Errors and Exceptions in Python</a></li>
                    <li><a href="https://www.w3schools.com/python/python_try_except.asp" target="_blank">W3Schools Python Try Except</a></li>
                    <li><a href="https://realpython.com/python-exceptions/" target="_blank">Real Python Python Exceptions: An Introduction</a></li>
                </ul>
            </section>

            <section id="construction-destruction" class="topic-section">
                <h2>Construction and Destruction in Python</h2>
                <ul>
                    <li>In object-oriented programming, construction (initialization) is handled by the <code>_init_</code> method, which is called when an object is created.</li>
                    <li>Destruction (cleanup) is handled by the <code>_del_</code> method, which is called when an object is about to be destroyed.</li>
                    <li>Python's garbage collection handles most object destruction automatically, so <code>_del_</code> is less commonly used.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
#Construction:
class add:
    def __init__(self,a,b):
        print(a+b)
a=add(5,5) #Output: 10

#Destruction:
class add:
    def __del__(self):
        print("5+5=10")
a=add()
del a #Output: 5+5=10
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://www.google.com/url?client=internal-element-cse&cx=e644b33a7719ef93e&q=https://prepinsta.com/python/constructor-destructor-in-python/&sa=U&ved=2ahUKEwibyJzDqZuMAxW7zTgGHcwGJzEQFnoECAoQAQ&usg=AOvVaw1rZ8FkJhb38fdHTOAiLTaK" target="_blank">Construction and Destruction in Python</a></li>
                    <li><a href="https://www.geeksforgeeks.org/destructors-in-python/" target="_blank">GeeksforGeeks Destructors in Python</a></li>
                    <li><a href="https://stackoverflow.com/questions/742475/why-is-del-not-called-in-python" target="_blank">Stack Overflow: Why is del not called in Python?</a></li>
                </ul>
            </section>

            <section id="python-mysql" class="topic-section">
                <h2>Connecting Python with MySQL</h2>
                <ul>
                    <li>Python can interact with MySQL databases using libraries like <code>mysql.connector</code>.</li>
                    <li>This allows you to perform database operations such as querying, inserting, updating, and deleting data.</li>
                    <li>You'll need to install the library using pip: <code>pip install mysql-connector-python</code>.</li>
                </ul>
                <h3>Code Example:</h3>
                <pre><code class="language-python">
import mysql.connector as sqltor
mycon=sqltor.connect(host="localhost",user="root",password="pass",database="student")
if mycon.is_connected()==False:
    print("error")
cursor=mycon.cursor()
cursor.execute(select * from student)
data=cursor.fetchall()
count=cursor.rowcount
for row in data:
    print(row)
mycon.close()
                </code></pre>
                <h3>Further Resources:</h3>
                <ul>
                    <li><a href="https://www.w3schools.com/python/python_mysql_create_db.asp" target="_blank">MySQL Create database</a></li>
                    <li><a href="https://dev.mysql.com/doc/connector-python/en/" target="_blank">MySQL Connector/Python Documentation</a></li>
                    <li><a href="https://www.w3schools.com/python/python_mysql.asp" target="_blank">W3Schools Python MySQL</a></li>
                    <li><a href="https://realpython.com/python-mysql/" target="_blank">Real Python Connecting to MySQL with Python</a></li>
                </ul>
            </section>

            <section id="" class="topic-section">
                <button onclick="myDialog.showModal()">Touch the button ... Please ...</button>
                <dialog id="myDialog">
                    <p>Thank You! for visiting my website. And I hope that something you've learned from my website. Once again, Thank You! for visiting my website.</p>
                    <button onclick="myDialog.close()">OK</button>
                </dialog>
                <script>
                    const myDialog = document.getElementById('myDialog');
                </script>      
            </section>
        </div>
    </main>

    <footer>
        <div class="footer-content">
            <div class="social-links">
                <h3>Contact Me</h3>
                <a href="mailto: yuvathilagan@gmail.com" target="__blank"><i class="fas fa-email"></i>yuvathilagan@gmail.com</a><br>
            </div>
            <div class="social-links">
                <h3>Follow Me</h3>
                <a href="https://www.instagram.com/_y_u_v_a_10_?igsh=MWJwaDhlYTY4OGg0ZA==" target="_blank"><i class="fab fa-instagram-f">Instagram</i></a>
                <a href="https://www.linkedin.com/in/yuva-thilagan-806681308?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><i class="fab fa-linkedin-in">LinkedIn</i></a>
                <a href="https://github.com/yuva-1237" target="_blank"><i class="fab fa-github">Github</i></a>
            </div>
        </div>
        <p>&copy; Terms and conditions:<marquee behaviour="scroll" direction="left"><br>I try my best, but I'm not the responsible if something goes wrong while you're using my website.At the same time, if you have any doubts or queries or clarification, check the resources.</marquee></p>
    </footer>
    </div>
    
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color:darkgrey;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background-color: black;
            color: #fff;
            padding: 1em 0;
            text-align: center;
            border-bottom: 2px solid #555;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
        }
        
        

        nav {
            margin-top: 1em;
        }

        .menu-toggle {
            display: none;
            background: none;
            border: none;
            color: #fff;
            font-size: 1.5em;
            cursor: pointer;
            padding: 0.2em 0.5em;
        }

        .main-nav {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        .main-nav li {
            margin: 0 1em;
        }

        .main-nav a {
            color: #fff;
            text-decoration: none;
            padding: 0.5em 1em;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .main-nav a:hover {
            background-color: #555;
        }

        main {
            padding: 20px 0;
        }

        .topic-section {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .topic-section h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
            margin-bottom: 15px;
            font-size: 1.8em;
        }

        .topic-section h3 {
            color: #555;
            margin-top: 15px;
            font-size: 1.4em;
        }

        .topic-section ul {
            list-style-type: disc;
            margin-left: 20px;
            margin-bottom: 10px;
        }

        .topic-section li {
            margin-bottom: 0.5em;
        }

        .topic-section pre {
            background-color: #272822;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
            margin-bottom: 15px;
        }

        .topic-section a {
            color: #007bff;
            text-decoration: none;
        }

        .topic-section a:hover {
            text-decoration: underline;
        }

        dialog {
            border: none;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
            padding: 24px;
            width: 400px; /* Adjust width as needed */
            max-width: 90%;
            background-color: #fff;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        dialog::backdrop {
            background-color: rgba(0, 0, 0, 0.4);
            backdrop-filter: blur(4px);
        }

        dialog p {
            font-size: 1.1em;
            color: #333;
            margin-bottom: 20px;
            line-height: 1.6;
        }

        dialog button {
            background-color: #007bff;
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s ease;
        }

        dialog button:hover {
            background-color: #0056b3;
        }

        button {
            background-color: #28a745;
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #218838;
        }

        footer {
            background-color:black;
            color: #f8f9fa;
            text-align: center;
            padding: 1.5em 0;
            border-radius: 0 0 8px 8px;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.1);
            margin-top: 30px;
        }

        .footer-content {
            display: flex;
            justify-content: space-around;
            align-items: flex-start;
            margin-bottom: 1em;
            padding: 0 2em;
        }

        .footer-content h3 {
            color: #fff;
            margin-bottom: 0.8em;
        }

        .footer-content .social-links a {
            color: #adb5bd;
            margin-bottom: 0.5em;
            text-decoration: none;
            transition: color 0.3s;
        }

        .footer-content .social-links a:hover {
            color: #fff;
        }

        .footer-content .social-links i {
            margin-right: 0.5em;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .main-nav {
                display: none;
                flex-direction: column;
                text-align: center;
                position: absolute;
                top: 60px; /* Adjust based on header height */
                left: 0;
                width: 100%;
                background-color: #333;
                z-index: 10;
            }

            .main-nav li {
                margin: 0;
            }

            .main-nav a {
                display: block;
                padding: 0.8em;
            }

            .menu-toggle {
                display: block;
            }

            .main-nav.show {
                display: flex;
            }
        }
    </style>

    <script src="script.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"></script>
    <script>hljs.highlightAll();</script>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
        const menuToggle = document.querySelector('.menu-toggle');
        const mainNav = document.querySelector('.main-nav');

        menuToggle.addEventListener('click', function() {
            mainNav.classList.toggle('show');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 50, // Adjust for header height
                        behavior: 'smooth'
                    });

                    // Close the menu if it's open
                    if (mainNav.classList.contains('show')) {
                        mainNav.classList.remove('show');
                    }
                }
            });
        });
    });
    </script>
</body>
</html>
