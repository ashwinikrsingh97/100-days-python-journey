# Day 02 Project: Tip Calculator

## Table of Contents
- [Overview](#overview)
- [My Process](#my-process)
- [Notes & Reflections](#notes--reflections)

---

## Overview

### The Challenge
- Build a tip calculator that takes the total bill, tip percentage, and number of people as inputs, then calculates how much each person should pay.

### Links
- 📂 Solution Code: [tip_calculator.py](./tip_calculator.py)
- 🎓 Course: [Angela Yu's 100 Days of Code](https://www.udemy.com/course/100-days-of-code/)

---

## My Process

### Built With
- Python 3

### What I Learned

| Concept | Example |
|---------|---------|
| `float()` | `bill = float(input("What was the total bill? "))` |
| `int()` | `people = int(input("How many people? "))` |
| Math operations | `total = bill * (1 + tip/100) / people` |
| Rounding | `round(total, 2)` |
| f-strings | `print(f"Each person should pay: ${total}")` |

### Useful Resources
- [Python Docs — Built-in Functions](https://docs.python.org/3/library/functions.html)

---

## Notes & Reflections

**What was easy:**
> The math logic was straightforward. Taking inputs and converting them to the right data type made sense quickly.

**What was tricky:**
> Remembering that `input()` always returns a string — so `float()` and `int()` conversions are needed before doing any math.

**How this applies to production support / BFSI work:**
> Type conversion is critical in BFSI scripts — e.g. reading numeric values from log files or config files always returns strings that need to be cast before calculations or comparisons.

**Time taken:** ~30–60 mins

---

*Part of my [100 Days of Python](../README.md) journey.*
