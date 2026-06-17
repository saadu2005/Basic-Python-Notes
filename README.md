# 🐍 Python Fundamentals
A comprehensive collection of Python programming concepts, examples, and exercises designed for beginners and intermediate developers.
________________________________________
## 📚 Topics Covered
## 🔄 Loops & Control Flow
+ 	For Loops
+ 	While Loops
+ 	Break Statement
+ 	Loop Exercises
## ⚙️ Functions
+	Function Definition
+	Parameters & Argu#ments
+	Return Statements
+	Scope (Local & Global)
+	Lambda Functions
+	Recursion
+	Docstrings
+	Best Practices
## 🛠 Built-in Functions
+	print()
+	input()
+	len()
+	range()
+	sum()
+	max()
+	min()
+	type()
________________________________________
________________________________________
##🔄 Python Loops
+ Loops allow a program to execute a block of code repeatedly.
+ For Loop
+ for i in range(1, 6):
 + print(i)
+ Output
+ 1
+ 2
+ 3
+ 4
+ 5
+ While Loop
+ count = 1

+ while count <= 5:
   + print(count)
  + count += 1
+ Break Statement
+ for i in range(1, 11):
   + if i == 5:
       + break
+    print(i)
________________________________________
## ⚙️ Python Functions
Functions are reusable blocks of code that perform specific tasks.
+ Function Definition
 + def greet():
    + print("Hello, World!")

 + greet()
 + Function with Parameters
+ def add(a, b):
   + return a + b

+ print(add(3, 5))
+ Output
+ 8
________________________________________
## 📥 Parameters & Arguments
+ Positional Arguments
+ def multiply(a, b):
   + return a * b

+ print(multiply(4, 5))
+ Default Arguments
+ def greet(name, message="Hello"):
   + return f"{message}, {name}"

+ print(greet("Saadi"))
+ Keyword Arguments
+ def user_info(name, age):
  +  print(name, age)

+ user_info(age=20, name="Saadi")
________________________________________
## ↩️ Return Statement
+ def square(number):
  +  return number * number

+ print(square(5))
+ Returning Multiple Values
+ def get_min_max(values):
  +  return min(values), max(values)

+ minimum, maximum = get_min_max([1, 5, 10])
________________________________________
## 🌍 Variable Scope
+ Global Scope
+ x = 10
+ Local Scope
+def example():
   + y = 5
________________________________________
## ⚡ Lambda Functions
+ square = lambda x: x ** 2

 + print(square(5))
________________________________________
## 🔁 Recursion
+ def factorial(n):
   + if n == 0:
       + return 1

   + return n * factorial(n - 1)

+ print(factorial(5))
________________________________________
## 📖 Docstrings
+ def multiply(a, b):
   + """
   + Returns the multiplication of two numbers.
   + """
   + return a * b
________________________________________
## 📋 Common Built-in Functions
+ Function	Purpose
+ len()	Returns length
+ print()	Displays output
+ input()	Reads user input
+ range()	Generates sequence
+ sum()	Calculates total
+ max()	Largest value
+ min()	Smallest value
+ type()	Returns data type
________________________________________
## 🎯 Practice Exercises
+ Loops
+	Print numbers from 1–20
+	Print even numbers from 2–20
+	Countdown from 10–1
+	Create a password checker
+	Stop a loop using break
## Functions
+	Calculate average of a list
+	Fibonacci using recursion
+	Even number checker using lambda
+	Maximum value using *args
+	Celsius to Fahrenheit converter
________________________________________
## ⚠️ Common Mistakes
+	Missing colon (:)
+	Forgetting return
+	Infinite recursion
+	Incorrect argument order
+	Modifying global variables improperly
+	Using mutable default arguments
_______________________________________
## 📂 Repository Structure
+ Python-Fundamentals/
│
├── README.md
├── Loops/
├── Functions/
├── Exercises/
└── Solutions/
________________________________________
## 🎓 Learning Objectives
+ By completing these examples, you will understand:
+	Python syntax fundamentals
+	Control flow and loops
+	Function design
+	Recursion
+	Scope management
+	Clean coding practices
________________________________________
## Author
+ ## Saadu
+ Python Developer + Problem Solver + Continuous Learner
