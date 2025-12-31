---
title: "Python Variables and Data Types Explained for Beginners"
datePublished: Wed Dec 31 2025 18:47:49 GMT+0000 (Coordinated Universal Time)
cuid: cmjudcbio000002lfbto27uar
slug: python-variables-and-data-types-explained-for-beginners
tags: variables, data-types, variables-and-constants, python-beginners

---

## ***What is a Variable in Python?***

* **Variable** consider as a **<mark>Container</mark>** or **<mark>Location</mark>** where we can store data.
    
* A **variable** is a name that refers to a value stored in memory.
    

**Example** :

name = "Tejaswini"

age = 23

**Here:**

* `name` stores a string
    
* `age` stores a number
    

Python automatically understands the data type.

## ***Rules for Naming Variables***

When creating variables in Python, follow these rules:

* Variable name must start with a letter or underscore
    
* Variable name cannot start with a number
    
* Variable names are case-sensitive
    
* No spaces allowed
    

### Valid variable names:

```plaintext
my_name = "Python"
_age = 20
totalMarks = 90
```

### Invalid variable names:

```plaintext
2name = "Wrong"
my name = "Wrong"
```

## *Constants in Python*

A **constant** is a variable whose value should **not be changed** once assigned.

⚠️ Python does **not** provide built-in constants like some other languages.  
Instead, Python uses a **naming convention** to represent constants.

### <mark>How to Declare a Constant</mark>

In Python, constants are written in **UPPERCASE letters**.

### Example:

```plaintext
PI = 3.14
MAX_USERS = 100
APP_NAME = "MyPythonApp"
```

### **By convention:**

* These values **should not be changed**
    
* Other developers understand that these are constants
    

### **Why Use Constants?**

Using constants helps:

* Improve code readability
    
* Avoid magic numbers
    
* Maintain consistency across the program
    

Example:

```plaintext
TAX_RATE = 0.18
total_tax = price * TAX_RATE
```

This is clearer than writing `0.18` everywhere.

---

## ***Python Data Types***

**<mark>Data type defines what kind of data or values a variable holds.</mark>**

Python has several built-in data types. Let’s understand the most commonly used ones.

### **Integer (int)**

Integers are **whole numbers** without decimal points.

### Example:

```plaintext
count = 10
score = -5
```

### **Float (float)**

Floats are numbers with **decimal points**.

### Example:

```plaintext
price = 99.99
percentage = 85.5
```

### **String (str)**

Strings are used to store **text** and are written inside quotes**(‘ ‘, “ “, ’’’ ‘‘‘).**

### Example:

```plaintext
message = "Hello Python"
language = 'Python'
```

### **Boolean (bool)**

Boolean data type stores only **True or False** values.

### Example:

```plaintext
is_active = True
is_logged_in = False
```

## ***Type Checking in Python***

* You can check the data type of a variable using the <mark> type() function</mark>.
    
* ### Example:
    

```plaintext
x = 10
print(type(x))
```

### **Output :**

<mark>&lt;class 'int'&gt;</mark>

## ***Dynamic Typing in Python***

Python is a **dynamically typed language**, which means you can change the data type of a variable.

### Example:

```plaintext
x = 10
x = "Python"
```

This is allowed in Python.

---

## ***Practice Examples***

Try writing these programs:

1. Store your name and age in variables
    
2. Add two numbers and print the result
    
3. Check the data type of different variables
    

**👍Practice will make these concepts clear.**

---

## ***Conclusion***

Variables help store data, and data types define what kind of data is stored.  
Once you understand variables and data types, learning Python becomes much easier.