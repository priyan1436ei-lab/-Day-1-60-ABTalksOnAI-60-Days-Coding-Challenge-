# Day 1 — 60 Days Coding Challenge

Welcome to **Day 1 of the 60 Days Coding Challenge**.

## 🚀 Python Mastery Sprint — Day 1

Before becoming a strong Software Engineer, it is important to be fluent in Python fundamentals.

This challenge focuses on learning and practicing the core basics of Python.

## 📚 Topics Covered

* Variables
* Data types

  * `int`
  * `float`
  * `str`
  * `bool`
* Type casting
* User input
* Output using `print()`
* Formatted strings using f-strings

## 🎯 Task

Create a Python program that:

1. Takes the user's name as input
2. Takes the user's age as input
3. Converts the age from string to integer
4. Calculates the user's age after 5 years
5. Prints a formatted message

## 💻 Solution

File:

`day1_basics.py`

```python
# Day 1 - Python Basics

name = input("Enter your name: ")
age = input("Enter your age: ")

age = int(age)

future_age = age + 5

print(
    f"Hello {name}, you are {age} years old. "
    f"In 5 years, you will be {future_age}."
)
```

## ▶️ Run the Program

```bash
python day1_basics.py
```

Or:

```bash
python3 day1_basics.py
```

## 🧪 Example Output

```text
Enter your name: Priyan
Enter your age: 19

Hello Priyan, you are 19 years old. In 5 years, you will be 24.
```

## 🧠 What I Learned

Through this challenge, I practiced:

* Creating and using variables
* Receiving user input with `input()`
* Understanding that `input()` returns a string
* Converting strings to integers with `int()`
* Performing arithmetic calculations
* Using Python f-strings for formatted output

## 📁 Project Structure

```text
.
├── day1_basics.py
└── README.md
```

## ✅ Challenge Status

**Day 1 Completed**

**60 Days Coding Challenge**

Next step: continue strengthening Python fundamentals through daily coding practice.

---

Made with 💻 by **Priyan**
