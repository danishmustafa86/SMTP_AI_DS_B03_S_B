## Module 1: Python


## Overall Goals

By the end of the course, you should be able to:

- **Write** small Python programs using variables, control flow, functions, and data structures.
- **Work with data**: strings, lists, dictionaries, files, and simple errors.
- **Solve basic algorithmic problems** (e.g. from LeetCode Easy).
- **Read and understand** other people’s simple Python code.
- **Use basic tooling**: running scripts, using an editor/IDE, reading error messages.

---

## Lecture 1 (Saturday – Week 1): Introduction & First Steps

**Main goals**
- Make students comfortable with the environment.
- Run their **first Python programs**.

**Topics**
- What is Python? Where it is used (web, data, AI, automation).
- Installing Python (if needed), using **VS Code**/**Cursor** or any editor of your choice.
- Running Python:
  - `python` / `python3` in terminal.
  - Running `.py` files.
- Python basics:
  - `print()` and comments (`#`).
  - Basic data types: integers, floats, strings, booleans.
  - Simple arithmetic: `+ - * / // %`.

**In‑class mini‑exercises**
- Print a welcome message with student’s name.
- Do simple calculations: area of a rectangle, sum of two numbers, etc.

**Homework idea (light, non‑LeetCode yet)**
- Ask students to write 3–4 very small scripts:
  - Greet the user by name.
  - Convert Celsius to Fahrenheit.
  - Compute the perimeter of a rectangle.

---

## Lecture 2 (Sunday – Week 1): Variables, Input & Basic Errors

**Main goals**
- Understand **variables** and **user input**.
- Learn to read basic error messages.

**Topics**
- Variables and assignment: `x = 5`, naming rules and good style.
- `input()` and `int()`, `float()` for converting.
- String concatenation vs `f-strings`.
- Introduction to basic errors:
  - Syntax errors (missing `)` or `:`).
  - Runtime errors (e.g. dividing by zero).
- `type()` to see variable type.

**In‑class mini‑exercises**
- Ask user for name and age, print a message: `"Hello Ali, you are 20 years old"`.
- Simple calculator: user inputs two numbers and an operator (`+` or `-`), program prints result.

**Practice**
- **Goal**: Comfortable with input, variables, basic math.

- **Suggested LeetCode Easy problems**
  - `1480. Running Sum of 1d Array` (if arrays are too early, let them try conceptually).
  - `1672. Richest Customer Wealth` (also simple addition).
- **Custom practice problems**
  - Given length and width from user, print area and perimeter of a rectangle.
  - Given two numbers, print which one is larger or if equal.
  - Convert minutes to hours and minutes (e.g., `130` minutes → `2 hours 10 minutes`).

---

## Lecture 3 (Saturday – Week 2): Conditions (if/elif/else)

**Main goals**
- Use `if`, `elif`, `else` to make decisions.

**Topics**
- Boolean expressions: `>`, `<`, `>=`, `<=`, `==`, `!=`.
- `if`, `elif`, `else` syntax (colon and indentation).
- Combining conditions with `and`, `or`, `not`.
- Nested `if` (briefly).

**In‑class mini‑exercises**
- Check if a number is positive, negative, or zero.
- Grading system: input a score (0–100) and print grade `A/B/C/D/F`.
- Simple login check: username and password (hard‑coded).

---

## Lecture 4 (Sunday – Week 2): More Conditions & Simple Programs

**Main goals**
- Practice conditions with small, real‑looking programs.

**Topics**
- Chained conditions: multiple `elif`.
- Simple menu programs using `if`/`elif`.
- Introduction to **logical thinking** with conditions (flow charts if helpful).

**In‑class mini‑exercises**
- Even or odd number checker.
- BMI calculator (ask for height and weight, categorize as underweight/normal/overweight etc.).
- Basic calculator with `if`/`elif` for `+ - * /`.

**Practice (after Lecture 3 & 4)**
- **Goal**: Confident with conditions and comparison.

- **Suggested LeetCode Easy problems**
  - `9. Palindrome Number` (only numeric version).
  - `412. Fizz Buzz` (great for conditions and loops; you can revisit next week with loops).
- **Custom practice problems**
  - Given a year, check if it is a leap year.
  - Student passes or fails based on multiple subject marks and overall average.
  - Simple traffic light: input color (`red`, `yellow`, `green`) and print what the driver should do.

---

## Lecture 5 (Saturday – Week 3): Loops – `while`

**Main goals**
- Understand **repetition** with `while`.
- Begin thinking in loops.

**Topics**
- Why we need loops (repeating tasks).
- `while` loop syntax.
- Loop variables and updating them.
- Infinite loops and how to avoid them.

**In‑class mini‑exercises**
- Print numbers 1 to 10 using `while`.
- Sum numbers from 1 to `n`.
- Guessing game: program chooses a fixed number, user keeps guessing until correct.

---

## Lecture 6 (Sunday – Week 3): Loops – `for`, `range`, and `break/continue`

**Main goals**
- Use `for` loops and `range`.
- Control loops with `break` and `continue`.

**Topics**
- `for` loop over `range(start, stop, step)`.
- Looping over characters in a string.
- `break` to stop a loop.
- `continue` to skip the current iteration.

**In‑class mini‑exercises**
- Print multiplication table for a number (e.g. 5).
- Count how many vowels are in a string.
- Print all numbers from 1 to 100 except multiples of 3 (using `continue`).

**Practice (after Lecture 5 & 6)**
- **Goal**: Comfortable with `for` and `while` loops.

- **Suggested LeetCode Easy problems**
  - `1342. Number of Steps to Reduce a Number to Zero`.
  - `383. Ransom Note` (loop through characters; even if they don’t use dicts yet, they can try).
- **Custom practice problems**
  - Print all even numbers between two given numbers.
  - Compute factorial of a number using a loop.
  - Reverse a string using a loop (no slicing yet, unless you want to show).

---

## Lecture 7 (Saturday – Week 4): Functions – Basics

**Main goals**
- Define and use **functions**.
- Understand parameters and return values.

**Topics**
- Why functions? Reuse, clarity, organization.
- Syntax: `def name(parameters):` and `return`.
- Local variables vs global (basic, not deep).
- Calling functions from `main` block (`if __name__ == "__main__":` can be mentioned but not required).

**In‑class mini‑exercises**
- Function to add two numbers and return the result.
- Function to check if a number is prime (simple implementation).
- Function to compute the average of 3 numbers.

---

## Lecture 8 (Sunday – Week 4): More Functions & Problem Decomposition

**Main goals**
- Break a problem into multiple functions.
- Practice passing and returning values.

**Topics**
- Multiple parameters.
- Default parameter values (optional).
- Functions calling other functions.
- Writing small utility functions and reusing them.

**In‑class mini‑exercises**
- Calculator using functions for each operation.
- Function to count vowels in a string.
- Function that takes a list of numbers and returns the max/min (you can preview lists here).

**Practice (after Lecture 7 & 8)**
- **Goal**: Comfortable writing and using functions.

- **Suggested LeetCode Easy problems**
  - `125. Valid Palindrome` (great for making helper functions).
  - `58. Length of Last Word`.
- **Custom practice problems**
  - Write a function to check if a number is perfect (sum of proper divisors = number).
  - Write a function that returns the greatest common divisor (GCD) of two numbers.
  - Write a function that takes a string and returns it in title case (first letter of each word capitalized).

---

## Lecture 9 (Saturday – Week 5): Lists – Basics

**Main goals**
- Use **lists** to store collections of values.

**Topics**
- Creating lists: `[]`, `[1, 2, 3]`.
- Accessing elements by index; negative indices.
- Basic operations:
  - `append`, `insert`, `pop`, `remove`.
  - `len()`.
- Iterating over lists with `for`.

**In‑class mini‑exercises**
- Store 5 student names in a list and print them one per line.
- Given a list of numbers, compute sum and average.
- Remove all occurrences of a given value from a list.

---

## Lecture 10 (Sunday – Week 5): More Lists & Basic List Algorithms

**Main goals**
- Practice solving small problems using lists.

**Topics**
- Slicing: `list[start:end:step]`.
- Searching for an element in a list.
- Finding max, min manually (without `max()`/`min()` first).
- Brief intro to list comprehensions (optional).

**In‑class mini‑exercises**
- Find the second largest number in a list.
- Remove duplicates from a list (simple approach using another list).
- Split a list into two lists: even numbers and odd numbers.

**Practice (after Lecture 9 & 10)**
- **Goal**: Confident manipulating lists and looping over them.

- **Suggested LeetCode Easy problems**
  - `217. Contains Duplicate`.
  - `136. Single Number`.
- **Custom practice problems**
  - Merge two sorted lists into one sorted list.
  - Rotate a list to the right by `k` steps (simple version).
  - Given a list of numbers, move all zeros to the end (order of others preserved).

---

## Lecture 11 (Saturday – Week 6): Strings in Detail

**Main goals**
- Work comfortably with **strings**.

**Topics**
- Indexing and slicing strings.
- Common methods: `lower()`, `upper()`, `strip()`, `split()`, `join()`, `replace()`.
- Checking membership: `in` / `not in`.
- Basic string formatting with `f-strings`.

**In‑class mini‑exercises**
- Count how many times a character appears in a string.
- Reverse words in a sentence.
- Check if a sentence is a palindrome (ignoring spaces and case).

---

## Lecture 12 (Sunday – Week 6): Dictionaries & Sets (Intro)

**Main goals**
- Understand **dictionaries** and **sets** conceptually and practically.

**Topics**
- Dictionaries:
  - Key–value pairs: `{"name": "Ali", "age": 20}`.
  - Accessing, adding, updating, deleting entries.
  - Iterating over keys, values, items.
- Sets:
  - Creation: `{1, 2, 3}` and `set()`.
  - No duplicates, membership tests.
  - Basic operations: union, intersection (brief).

**In‑class mini‑exercises**
- Store student info in a dictionary and print formatted output.
- Count word frequencies in a sentence (very basic word count).
- Given two lists, find common elements using sets.

**Practice (after Lecture 11 & 12)**
- **Goal**: Comfortable with strings, dictionaries, sets for basic problems.

- **Suggested LeetCode Easy problems**
  - `387. First Unique Character in a String`.
  - `242. Valid Anagram`.
- **Custom practice problems**
  - Given a sentence, output the top 3 most frequent words.
  - Replace all repeated characters in a string with `*` except the first occurrence.
  - Build a mini phonebook using a dictionary (name → phone), allow simple lookup.

---

## Lecture 13 (Saturday – Week 7): Files & Basic Error Handling

**Main goals**
- Read from and write to text files.
- Handle simple errors with `try/except`.

**Topics**
- Opening files with `with open(...) as f:`.
- Reading content: `read()`, `readline()`, `readlines()`.
- Writing to files: mode `"w"`, `"a"`.
- Intro to exceptions: `try`, `except`, optional `finally`.

**In‑class mini‑exercises**
- Read a text file and print each line with line numbers.
- Write user input to a file (like a simple note‑taking program).
- Safely read a file that may not exist (handle `FileNotFoundError`).

---

## Lecture 14 (Sunday – Week 7): Putting It Together – Small Project

**Main goals**
- Combine **functions, loops, lists, strings, files** in a small program.

**Topics**
- Planning a small project:
  - Example: **To‑Do List app**, **Student grade manager**, or **Simple contact manager**.
- Breaking project into functions and modules.
- Basic saving/loading data from files.

**In‑class activity**
- Guide students step‑by‑step through building a small project, e.g.:
  - **To‑Do app**  
    - Add a task.  
    - List tasks.  
    - Mark task as done.  
    - Save tasks to a file.

**Practice (after Lecture 13 & 14)**
- **Goal**: Apply all core Python knowledge in a slightly larger program.

- **Suggested LeetCode Easy problems**
  - `20. Valid Parentheses`.
  - `929. Unique Email Addresses`.
- **Custom practice problems**
  - Extend the class project (e.g. add search, sorting, or simple filtering).
  - Write a program that reads a file and prints:
    - Number of lines
    - Number of words
    - Number of characters

---

## Lecture 15 (Saturday – Week 8): Intro to Modules & Standard Library

**Main goals**
- Introduce modules and Python’s standard library.

**Topics**
- What is a module? How to `import`:
  - `import math`
  - `from random import randint`
- Using some basic modules:
  - `math` (sqrt, ceil, floor).
  - `random` (randint, choice).
  - `datetime` (current date and time).
- Organizing code across multiple files (brief).

**In‑class mini‑exercises**
- Simple random number games (guess the number).
- Generate a random password (letters/digits).
- Print current date and time in a nice format.

---

## Lecture 16 (Sunday – Week 8): Review, Practice, and Next Steps

**Main goals**
- Review all key concepts and practice problem‑solving.
- Show students where to go next.

**Topics**
- Quick recap:
  - Variables, types, conditions, loops.
  - Functions.
  - Lists, strings, dicts, sets.
  - Files and error handling.
- Walk through 2–3 small end‑to‑end problems.
- Discuss next steps: OOP, more algorithms, data analysis, web dev, etc.

**In‑class activity**
- Solve 2–3 LeetCode Easy problems live, step‑by‑step.
- Ask students to explain their ideas before coding.

**Final practice (after Lecture 15 & 16)**
- **Suggested LeetCode Easy problems**
  - `1. Two Sum`.
  - `13. Roman to Integer`.
- **Custom practice problems**
  - Design and implement a small project of their choice using what they learned (you can give 2–3 suggested ideas).

---



