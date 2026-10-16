# Weekly Assignment: Python Practice (Levels 1 to 3)

A set of Python practice problems organized into three difficulty levels. Each level is a Jupyter notebook, and each problem is a separate code cell with a comment describing the task.

## Contents

| File | Level | Topics covered |
|---|---|---|
| `Level 1 - Basics.ipynb` | Basics | Input/output, conditionals, loops, strings, lists, prime numbers, Fibonacci, factors, perfect numbers, Floyd's triangle |
| `Level 2 - Medium.ipynb` | Medium | List comprehensions, user-defined functions, list manipulation, pattern printing, exception handling (`try`/`except`), a menu-driven calculator |
| `Level 3 - Hard.ipynb` | Hard | Recursion (factorial, Fibonacci, digit sum, string reversal, Tower of Hanoi, palindrome check, flattening nested lists), list comprehensions with helper functions, a read-until-stop loop with statistics, a Student Record Management System |

## Level 1: Basics

- Calculate total, percentage, and grade from five subject marks
- Check for a leap year
- Find the largest and second largest of three numbers
- Calculate an electricity bill using tiered rates
- Check for an Armstrong number
- Slice a string (first three, last three, every alternate character) and reverse it
- Count vowels, consonants, digits, and special characters
- Check for a palindrome using slicing
- Count the frequency of each character
- Remove spaces from a string and count words
- Print all primes up to N
- Print the first N Fibonacci terms
- Find all factors of a number
- Check for a perfect number
- Print Floyd's triangle up to N rows
- Find the largest, smallest, and average of a list
- Remove duplicates while keeping the original order
- Find the second largest and second smallest in a list
- Separate even and odd numbers
- Rotate a list left by K positions

## Level 2: Medium

- Build lists with list comprehensions (squares, primes, uppercase strings, word lengths, removing empty strings)
- Write functions for prime checking, GCD, second largest element, longest word, and merging lists without duplicates
- Find common elements between two lists without using sets
- Find the missing number from 1 to N
- Count the frequency of each element in a list
- Sort a list without `.sort()` (bubble sort)
- Print a diamond pattern of stars
- Handle errors with `try`/`except`: division by zero, invalid integer input, `IndexError`, and `FileNotFoundError`
- Build a menu-driven calculator

## Level 3: Hard

- Solve recursive problems: factorial, Fibonacci, sum of digits, string reversal, palindrome check, and flattening nested lists
- Solve Tower of Hanoi and print the sequence of moves
- Use a helper function inside a list comprehension to find primes
- Read numbers until the user types `stop`, then report statistics
- Build a Student Record Management System with functions for adding, viewing, and managing records

## How to Run

1. Install Jupyter (`pip install notebook`) or open the files in VS Code or Google Colab.
2. Open a notebook and run the cells from top to bottom.
3. Problems that ask for input will prompt you in the cell output. Type your answer and press Enter.

Level 2 includes a file-handling exercise that opens `data.txt`. If the file is not present, the program prints a "file not found" message, which is expected.

## Requirements

- Python 3.8 or newer
- Jupyter Notebook, JupyterLab, VS Code, or Google Colab
- No external libraries are required. Every solution uses only the Python standard library.
