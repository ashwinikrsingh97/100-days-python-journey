# Day 03 Project: Treasure Island

## Table of Contents
- [Overview](#overview)
- [My Process](#my-process)
- [Notes & Reflections](#notes--reflections)

---

## Overview

### The Challenge
- Build a text-based adventure game where the user makes choices at each stage. Wrong choices lead to a "Game Over", the right path leads to the treasure.

### Links
- 📂 Solution Code: [treasure_island.py](./treasure_island.py)
- 🎓 Course: [Angela Yu's 100 Days of Code](https://www.udemy.com/course/100-days-of-code/)

---

## My Process

### Built With
- Python 3

### What I Learned

| Concept | Example |
|---------|---------|
| `if` / `elif` / `else` | `if choice == "left":` |
| Nested conditionals | `if` inside another `if` block |
| `.lower()` | `choice = input().lower()` — handles uppercase input |
| String comparison | `if choice == "swim":` |
| ASCII art | Multi-line `print()` for game visuals |

### Useful Resources
- [Python Docs — Control Flow](https://docs.python.org/3/tutorial/controlflow.html)

---

## Notes & Reflections

**What was easy:**
> Writing the `if/elif/else` blocks was intuitive once the story logic was mapped out.

**What was tricky:**
> Nesting conditionals — keeping track of which `if` belongs to which level got a bit confusing at first. Indentation is everything in Python.

**How this applies to production support / BFSI work:**
> Conditional logic is the backbone of incident triage scripts — e.g. "if error code is X, trigger alert Y; elif error code is Z, auto-restart service." Same pattern, real-world stakes.

**Time taken:** ~30–60 mins

---

*Part of my [100 Days of Python](../README.md) journey.*
