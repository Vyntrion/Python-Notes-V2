
# 🐍 Python Notes V2: From Basics to Advanced  
> **Created with ❤️ by Vyntrion**

---

## 🧠 What is Python?

Python is a **high-level**, **interpreted**, **general-purpose** programming language.  
It emphasizes **code readability** with its clean syntax and supports multiple programming paradigms (OOP, functional, procedural).

---

## 🧪 How Python Runs

1. Python code (`.py`) is interpreted line-by-line.
2. No need to compile.
3. Use `python filename.py` in terminal/command prompt to run.

---

## 🧰 Python Installation

- Install from [https://python.org](https://python.org)
- Use IDEs: **VS Code**, **PyCharm**, **Thonny**, or online platforms like **Replit**, **Jupyter Notebook**

---

## 📌 Python Syntax Basics

### 🟩 Comments
```python
# This is a comment
"""This is a multi-line comment"""
```

### 🟩 Printing Output
```python
print("Hello World")  # Displays message
```

### 🟩 Getting Input
```python
name = input("Enter your name: ")
```

---

## 📊 Data Types

| Type     | Example         | Description              |
|----------|------------------|--------------------------|
| int      | `10`, `-4`       | Integer numbers          |
| float    | `3.14`           | Decimal numbers          |
| str      | `"Hello"`        | Text/String              |
| bool     | `True`, `False`  | Boolean logic            |
| list     | `[1,2,3]`        | Ordered, mutable         |
| tuple    | `(1,2,3)`        | Ordered, immutable       |
| dict     | `{"a": 1}`       | Key-value pairs          |
| set      | `{1, 2, 3}`      | Unique unordered values  |

---

## 🧠 Variables

```python
x = 5           # integer
name = "Alice"  # string
is_cool = True  # boolean
```

Variable names:
- Should start with a letter or `_`
- Cannot start with numbers
- Are case-sensitive

---

## 🔄 Type Conversion
```python
int("5")     # 5
str(123)     # "123"
float("3.14") # 3.14
bool(0)      # False
```

---

## 🔁 Operators

### 🔢 Arithmetic
```python
+  # Addition
-  # Subtraction
*  # Multiplication
/  # Division
%  # Modulus (Remainder)
// # Floor division
** # Power
```

### 🔀 Comparison
```python
==  # Equal
!=  # Not equal
>   # Greater than
<   # Less than
>=  # Greater or equal
<=  # Less or equal
```

### 🔧 Logical
```python
and, or, not
```

---

## 🧭 Control Flow

### 🔹 if, elif, else
```python
age = 18
if age >= 18:
    print("Adult")
elif age > 13:
    print("Teen")
else:
    print("Child")
```

---

## 🔁 Loops

### 🔄 For Loop
```python
for i in range(5):
    print(i)
```

### 🔄 While Loop
```python
count = 0
while count < 5:
    print(count)
    count += 1
```

---

## 📦 Data Structures (In Detail)

### 🟡 Lists
```python
my_list = [1, 2, 3]
my_list.append(4)
my_list.remove(2)
print(my_list[0])
```

### 🔵 Tuples
```python
my_tuple = (1, 2, 3)
print(my_tuple[1])
```

### 🟣 Sets
```python
my_set = {1, 2, 3, 2}
my_set.add(4)
```

### 🟠 Dictionaries
```python
my_dict = {"name": "Vanshu", "age": 16}
print(my_dict["name"])
```

---

## 🧩 Functions

```python
def greet(name):
    return "Hello " + name

print(greet("Vyntrion"))
```

---

## 📦 Modules & Libraries

### Built-in Modules
```python
import math
print(math.sqrt(16))
```

### Installing External Libraries
```bash
pip install requests
```

---

## ⚙️ OOP in Python

### 🧱 Class & Object
```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(self.name + " says Woof!")

d = Dog("Tommy")
d.bark()
```

### Concepts:
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction

---

## 🔥 Advanced Python

### List Comprehension
```python
squares = [x**2 for x in range(10)]
```

### Lambda Functions
```python
add = lambda x, y: x + y
print(add(5, 3))
```

### Map / Filter / Reduce
```python
from functools import reduce

nums = [1, 2, 3, 4]

doubled = list(map(lambda x: x*2, nums))
evens = list(filter(lambda x: x%2==0, nums))
summed = reduce(lambda a, b: a+b, nums)
```

---

## 📂 File Handling
```python
# Writing
with open('file.txt', 'w') as f:
    f.write("Hello")

# Reading
with open('file.txt', 'r') as f:
    print(f.read())
```

---

## 🛠️ Error Handling
```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Error: Cannot divide by zero!")
finally:
    print("Done.")
```

---

## 🧪 Useful Built-in Functions
```python
len(), type(), range(), input(), print(), sum(), sorted(), min(), max()
```

---

## 💻 Projects to Try

- Calculator
- Number Guessing Game
- To-Do List App
- Weather App with API
- Discord Bot
- Snake Game (with pygame)
- Chatbot (with NLTK or GPT)

---

## 🧾 Final Tips

- Practice daily.
- Build real-world projects.
- Debug by reading error messages.
- Join coding communities.
- Ask for help when stuck.

---

## 🏁 Credits

**Made by Vyntrion**  
Keep going. You’re doing great 💙

---

📝 This is the **v2** of Python Notes.  
All concepts explained clearly and command-wise with examples.
