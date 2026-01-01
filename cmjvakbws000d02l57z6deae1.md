---
title: "Python Character Set, print() Function, and ASCII Values Explained"
datePublished: Thu Jan 01 2026 10:17:50 GMT+0000 (Coordinated Universal Time)
cuid: cmjvakbws000d02l57z6deae1
slug: python-character-set-print-function-and-ascii-values-explained
tags: ascii, python, programming-languages

---

Before writing complex Python programs, it is important to understand some **basic building blocks** of the language.

In this blog, we will learn:

✔ What the **Python character set** is

✔ How the **print() function** works

✔ What **ASCII values** are and why they matter

## ***Python Character Set***

* A **character set** is a collection of **valid characters** that a programming language understands.
    
* Python supports a wide range of characters, making it flexible and powerful.
    

**Python Character Set Includes:**

**1\. Letters**

* Uppercase letters: <mark>A to Z</mark>
    
* Lowercase letters: <mark>a to z</mark>
    

**2\. Digits**

* <mark>0 to 9</mark>
    

**3\. Special Characters**

* <mark>+ - * / %</mark>
    
* <mark>@ # $ &amp;</mark>
    
* <mark>() [] {}</mark>
    

**4\. White Spaces**

* <mark>Space</mark>
    
* <mark>Tab</mark>
    
* <mark>New Line</mark>
    

**5\. Unicode Characters**

* Python supports Unicode, so it can handle characters from many languages.
    

Example:

name = "Tejaswini"

number = 10

All characters used above belong to Python’s character set.

## ***The <mark>print()</mark> Function in Python***

* The `print()` function is used to **display output** on the screen.
    
* It is one of the **most commonly used functions** in Python.
    

### **Basic Usage of print()**

### Example:

```plaintext
print("Hello, Python!")
```

### Output:

```plaintext
Hello, Python!
```

---

### **Printing Variables**

You can print the value of variables using `print()`.

### Example:

```plaintext
name = "Python"
print(name)
```

### Output:

```plaintext
Python
```

---

### **Printing Multiple Values**

You can print multiple values by separating them with commas.

### Example:

```plaintext
print("My age is", 23)
```

### Output:

```plaintext
My age is 23
```

---

### **The sep Parameter in print()**

The `sep` parameter changes the **separator** between values.

### Example:

```plaintext
print("Python", "DSA", "Learning", sep=" - ")
```

### Output:

```plaintext
Python - DSA - Learning
```

---

### **The end Parameter in print()**

By default, `print()` moves to a new line after printing.

The `end` parameter changes this behavior.

### Example:

```plaintext
print("Hello", end=" ")
print("World")
```

### Output:

```plaintext
Hello World
```

---

## ***What are ASCII Values?***

* **ASCII (American Standard Code for Information Interchange)** is a numeric representation of characters.
    
* Each character is assigned a **unique number**.
    
* Examples:
    
    * `A` → 65
        
    * `a` → 97
        
    * `0` → 48
        
    
    Python uses these values internally to store and compare characters.
    

### **Important Patterns (Easy to Remember)**

* **A–Z → 65 to 90**
    
* **a–z → 97 to 122**
    
* **0–9 → 48 to 57**
    
* Uppercase letters come **before** lowercase
    
* ASCII is **case-sensitive**
    

---

### **Getting ASCII Value in Python**

You can use the `ord()` function to get the ASCII value of a character.

### Example:

```plaintext
print(ord('A'))
print(ord('a'))
print(ord('1'))
```

### Output:

```plaintext
65
97
49
```

---

### **Getting Character from ASCII Value**

You can use the `chr()` function to convert an ASCII value to a character.

### Example:

```plaintext
print(chr(65))
print(chr(97))
```

### Output:

```plaintext
A
a
```

---

### **Why ASCII Values Are Important**

ASCII values are useful for:

* Character comparison
    
* Sorting strings
    
* Understanding how characters are stored
    
* Solving DSA problems involving strings
    

Example:

```plaintext
print('A' < 'B')
```

Output:

```plaintext
True
```

**This happens because ASCII value of** `A` **is less than** `B`**.**

---

## Conclusion

Python supports a rich character set, the `print()` function helps display output, and ASCII values define how characters are stored internally.

## ***Happy coding!!!!***