<h1 style ="color:red; text-align: center">Learn Python Programming - Basics </h1>

## 📌 What is Python❔
<p>Python is one of the most popular programming languages. It's simple to use, packed with features and supported by a wide range of libraries and frameworks. It's clean syntax makes it beginner-friendly. It's </p>

- A high-level language, used in web development, data science, automation, AI and more.
- Known for its readability, which means code is easier to write, understand and maintain.
- Backed by library support, so we don't have to build everything from scratch. there's probably a library that already does what we need.

## 📌 Recommended Editor
- VS Code
- PyCharm
- Jupyter Notebook(for data tasks)

## First Program in Python

Here is a simple Python code, printing a string.

```py
print("Hello World!")
```
**Output**
```py
Hello World!
```
## 📌 Variables and Data Types
**What is a Variable❔**

In Python, variables are used to store data that can be referenced and manipulated during programming execution. A variable is essentially a name that is assigned toa value. Unlike many other programming languages, Python variables do not require explicit declaration of type. The type of the variable is inferred based on the value assigned.<br><br>
Variables act as placeholders for data. They allow us to store and reuse values in our program.

```py
# Variable 'x' stores the integer value 10
x = 10

# Variable 'name' stores the string "Sudhir"
name = "Sudhir"

print(x)
print(name)
```
*Output*
```py
10
Sudhir
```
## 📌 Rules for Naming Variables
To use variables effectively, we must follow Python's naming rules:

- Variable names can only contain letters, digits and underscores(_).
- A variable name cannot start with a digit.
- Variable names are case-sensitive (myvar and myVar are different).
- Avoid using Python Keywords(e.g.if, else, for) as variable names.

#### Valid Example:

```py
age = 21
_colour = "lilac"
total_score = 90
```

#### Invalid Example:
```py
1name = "Error" # Starts with a digit
class = 10   # 'class' is a reserved keyword
user-name = "Doe"  # Contains a hypen
```

## 📌 Data Types

| Type                | Example           | Description          |
| :-----------------  | :---------------: | :------------------- |
| `int`               | `5`, `-10`        | Integer numbers      |
| `float`             | `3.14`, `-2.0`    | Decimal numbers      |
| `str`               | `"Hello"`         | Text data (strings)  |
| `bool`              | `True`, `False`   | Boolean values       |
| `NoneType`          | `None`            | Represents no value  |

```py
a = 10   # int
b = 3.14  # float
c = "Hello"   #str
d = True  # bool
e = None  # NoneType
```
### Type Checking

```py
a = 10
b = 3.14
c = "Sudhir"
d = True
e = None
print(type(a))
print(type(b))
print(type(c))
print(type(d))
print(type(e))
```

*Output*
```py
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>
<class 'NoneType'>
```
## 📌 Input and Output in Python
Understanding input and output operations is fundamental to Python programming. With the print() function, we can display output in various formats, while the input() funcion enables interaction with users by gathering input during program execution.

### Taking input in Python
Python's input() function is used to take user input. By default, it returns the user input in form of a string.

**Example**
```py
name = input("Enter your name: ")
print("Hello,", name, "! Welcome!")
```
*Output:*
```py
Enter your name:  Sudhir
Hello, Sudhir ! Welcome!
```
### Printing Output using print() in Python
At its core, printing output in Python is straightforward. This function allows us to display text, vaiables and expressions on the console. Let's begin with the basic usage of the print() function:

**Example**
```py
print("Hello Sudhir")
```

*Output:*
```py
Hello Sudhir
```
### Printing Variables
We can use the print() function to print single and multiple variables. We can print multiple variables by separating them with commas.

**Example:**

```py
# Single variable

s = "Sudhir"
print(s)

# Multiple Variables

s = "Jhon"
age = 25
city = "Mumbai"
print(s, age, city)
```
*Output:*
```py
Sudhir
Jhon 25 Mumbai
```
## 📌 Type Casting in Python
Type Casting means converting one data type to another.

```py
x = int("10")  # from str to int
y = float("5.5")  # from str to float
z = str(123) # from int to str
```

## 📌 Operators in Python 

### 📍 Arithmatic Operators:

|Operator    | Name            | Example   |
|:----------:|:--------------- |:---------:|
|     +      | Addition        |  x + y    |
|     -      | Substraction    |  x - y    |
|     *      | Multiplication  |  x * y    |
|     /      | Division        |  x / y    |
|     %      | Modulus         |  x % y    |
|    **      | Exponention     |  x ** y   |
|    //      | Floor Division  |  x // y   |
|            |                 |           |

**Example Addition :**
```py
x = 25
y = 4

# Addition
print("Addition :", x + y)

# Substraction
print("Substraction :", x - y)

# Multiplication
print("Multiplication :", x * y)

# Division
print("Division :", x / y)

# Modulus
print("Modulus :", x % y)

# Exponention
print("Exponention :", x ** y)

# Floor Division
print("Floor Division :", x // y)
```
*Output:*
```py
Addition : 29
Substraction : 21
Multiplication : 100
Division : 6.25
Modulus : 1
Exponention : 390625
Floor Division : 6
```

### 📍 Comparison Operators:

Comparison operators are used to compare two values:

| Oerator   | Name                       | Example    |
|:---------:|:---------------------------|:-----------|
| ==        | Equal                      | x == y     |
| !=        | Not Equal                  | x != y     | 
| >         | Greater than               | x == y     | 
| <         | Less than                  | x == y     | 
| >=        | Greater than or Equal to   | x == y     | 
| <=        | Less than or Equal to      | x == y     | 
|           |                            |            |

**Example Comparison Operators :**
```py
a = 10
b = 3
c = 10

print (a>b)
print (a<b)
print (a == c)
print (a != b)
print (a >= c)
```
*Output:*
```py
True
False
True
True
True
```

### 📍 Logical Operators:

Logical operators are used to combine conditional statements.

| Oerator   | Description                                             | Example               |
|:---------:|:--------------------------------------------------------|:----------------------|
| and       | Returns True if both statements are true                | x < 5 and x < 10      |
| or        | Returns True if one of the statements is true           | x < 5 or  x < 10      |
| not       | Reverse the result, returns False if the result is true | not(x < 5 and x < 10) |

**Example Logical Operators :**
```py
x = 10
y = 12

print (x < 3 and x < 10)
print (y > x or x > y)
print (not (x > 3 and x < y))
```
*Output*
```py
False
True
False
```
## 📌 Conditional Statments (if, elif, else)

Conditional statments in Python are used to execute certain blocks of code based on specific conditions. 
These statements help control the flow of a program, making it behave differently in different situations.

### Basic Syntax:
```py
if condition:
    # Code block (runs if condition is true)
elif another_condition:
    # runs if first condition is false but this is true
else:
    # runs if none of the above are true 

```
***Indentation is important in Python (usually 4 spaces or a tab)***

### 📍 If Conditional Statement:
If statement is the simplest form of a conditional statement. It executes a block of code if the given condition is true.

**Example**
```py
age = 20
if age >= 18:
    print("Eligible to vote.")
```
*Output*
```py
Eligible to vote.
```
### 📍 If else Conditional Statement:
If Else allows us to specify a block of code that will execute of the condition(s) associated with an if or elif statement evaluates to False.
Else block provides a way to handle all other cases that don't meet the specified conditions.

**Example**
```py
age = 15
if age >= 18:
    print("Eligible to vote.")
else:
    print("You are not eligible to vote.")
```
*Output*
```
You are not eligible to vote.
```
### 📍 elif Statement:
elif statement in Python stands for "else if". It allows us to check multiple conditions, providing a way to execute different blocks of code based on which condition is true. 
Using elif statments makes our code more readable and efficient by eliminating the need for multiple nested if statements.

**Example**
```py
age = 25
if age <= 12:
    print("Child")
elif age <= 19:
    print("Teenager")
elif age <= 35:
    print("Young adult")
else:
    print("Adult")
```

*Output:*
```py
Young adult
```
<hr>

## 📌 Loops (for, while, break, continue)

**What is a Loop**
A **loop** is used to **execute a block of code repeatedly** until a certain condition is met or a range is exhausted.
- Avoid writing repetitive code manually
- Useful for processing data, automating tasks, and controlling program flow

## Types of Loops in Python

**1. for Loop**
- Used when you **know how many times** you want to loop (usually over a collection or a range).
- Iterates over iterable objects (like lists, strings, tuples, range, etc.)

**Example**
```py
for i in range(3):
    print("Hello")
```

*Output:*
```py
Hello
Hello
Hello
```

**2. while Loop**
- Use when you **don't know how many times to loop - but you know the condition.
- Keeps running while the condition is True

**Example**

```py
x = 1
while x <= 3:
    print("Hi")
    x += 1
```
```py
Hi
Hi
Hi
```
### Key Loop Concepts
**rang() Function (for use with for)**
- Returns a sequence of numbers.
- range(start, stop, step)

```py
range(5)        → 0, 1, 2, 3, 4  
range(2, 6)     → 2, 3, 4, 5  
range(1, 10, 2) → 1, 3, 5, 7, 9
```
#### Loop Control Statements:

| Keyword   | Description                                  |
|:----------|:---------------------------------------------|
| break     | Exit the loop immediately                    |
| continue  | Skip the current iteration and continue      |
| else      | Runs when loop finishes naturally (no break) |
|           |                                              |

#### When to Use for vs while

| Use Case                            | Best Loop     |
|:------------------------------------|:--------------|
| Iterating over items                | for loop      |
| Looping a known numbers of times    | for loop      |
| Waiting for a condition to be true  | while loop    |
| Creating infinite loops (with exit) | while loop    |
|                                     |               |

#### Real-World Examples

| Use Case                     | Loop Type     | Example                |
|:-----------------------------|:--------------|:-----------------------|
| Reading 1000 files           | for loop      | for file in files:     |
| Taking input until valid     | while loop    | while not valid_input: |
| Searching for a value        | for + break   | for item in list:      |
| Skipping certain conditions  | continue      | if value < 0: continue |
|                              |               |                        |

#### Common Mistakes to Avoid
- **Forgetting to update condition in while loops** → leads to infinite loops
- **Wrong indentation** → Python uses indentation to define blocks
- **Off-by-one errors** → Remember range(n) goes from 0 to n-1

#### *Important!*

| Keyword     | Purpose                                   |
|:------------|:------------------------------------------|
| for         | Loop over a sequence (list, range etc..)  |
| while       | Loop as long as a condition is True       |
| break       | Exit loop early                           |
| continue    | Skip to the next iteration                |
| else        | Runs after loop only if not broken        |
|             |                                           |

<hr>

## 📌 Functions (def, parameters, return)

**What is a Function❔**
A function is a reusable block of code designed to perform a specific task.
Function make your code modular, organized, and easier to debug.

### 1. Creating a Function

#### Syntax:
```py
def function_name(parameters):
    # code block
    return result
```

**Example**
```py
def greet(name):
    print(f"Hello, {name}!")
# To call the function:
greet("Sudhir")
```
*Output:*
```py
Hello, Sudhir!
```

### 2. return vs print
- print() → Displays the result on screen
- return → Gives the result back to the caller for further use

```py
def square(x):
    return x * x
result = square(5)
print("Output is:", result)
```
*Output:*
```
Output is: 25
```
### 3. Parameters and Arguments
```py
def add(a, b):
    return a + b

print("Output is:", add(2,3))
```
*Output:*
```py
Output is: 5
```

**Types of Parameters**

| Type             | Example                   |
|:-----------------|:--------------------------|
| Positional       | add(2,3)                  |
| Default          | def greet(name="Guest")   |
| Keyword          | greet(name="Sudhir")      |
| Variable-length  | *args, **kwargs           |
|                  |                           |

### 4. Default Parameters

```py
def greet(name="Guest"):
    print("Hello,",name)

greet()
greet("Yuvika")
```
*Output:*
```py
Hello, Guest
Hello, Yuvika
```

### 5. Variable-Length Arguments

🔷 *args = multiple positional arguments

```py
def total(*numbers):
    return sum(numbers)

print("The sum is:", total(1, 2, 3))
```
*Output:*
```
The sum is: 6
```
🔷 **kwargs = multiple keyword arguments

```py
def profile(**info):
    print(info)

profile(name="Sudhir", age=30)
```
*Output:*
```
{'name': 'Sudhir', 'age': 30}
```

### 6. Function Scope

**Variable inside a function are local by default:**
```py
def test():
    x = 10
    print(x)

test()
```
To use **global variables:**
```py
x = 5

def update():
    global x
    x = 10

update()
print("The value of x is:" , x)
```
*Output:*
```
The value of x is: 10
```
### 7. Lambda Functions (Anonymous Functions)
Used for simple one-liners.

```py
square = lambda x: x * x
print("The square is:", square(4))
```
*Output:*
```
The square is: 16
```

### Sumamry Table:

|Concept       | Description                            |
|:-------------|:---------------------------------------|
| def          | Used to define a function              |
| return       | Gives back result to caller            |
| *args        | Accepts any number of positional args  |
| **kwargs     | Accepts any number of keyword args     |
| lambda       | Anonymous function                     |
| Local Scope  | Variable inside a function             | 
| Global Scope | Variable outside a function            |
|              |                                        |
<hr>