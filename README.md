# Fix My Code Challenge

## Description

"Fix My Code" is a unique project where we dive into existing code bases and fix issues. This project involves debugging code in different programming languages (Python, JavaScript, Ruby, and C) without having to recode everything from scratch.

## Background Context

This project is designed to help develop debugging skills across various languages. Some of these languages might be familiar, while others might be new. The goal is to find what's wrong with the provided code and implement minimal fixes to make it work correctly.

## Requirements

### General
- Allowed editors: vi, vim, emacs
- All files will be compiled on Ubuntu 20.04 LTS
- All files should end with a new line
- A README.md file at the root of the project folder is mandatory

## Tasks

### 0. FizzBuzz (Python)
**Issue**: The implementation of FizzBuzz in Python has a bug where numbers that are multiples of both 3 and 5 (like 15) are printing "Fizz" instead of "FizzBuzz".

**Current Output**:
```
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
```

**Expected Behavior**: Numbers that are multiples of both 3 and 5 should print "FizzBuzz".

### 1. Print Square (JavaScript)
**Issue**: The implementation of printing a square in JavaScript is producing incorrect output when given a size of 10.

**Current Output**:
```
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
```

**Expected Behavior**: The square should be 10x10 characters in size.

### 2. Sort (Ruby)
**Issue**: The implementation of sorting arguments in Ruby is not working correctly.

**Current Output**:
```
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
```

**Expected Behavior**: The program should sort integers in ascending order and ignore non-integer arguments.

### 3. User Password (Python)
**Issue**: The implementation of a User class in Python has a bug related to password validation.

**Current Output**:
```
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
```

**Expected Behavior**: The tests should not print any error messages if the implementation is correct.

### 4. Double Linked List (C)
**Issue**: The implementation of a Double linked list in C has issues with the delete operation.

**Expected Behavior**: The double linked list operations should work correctly, particularly when deleting nodes.

## Repository Structure

- `0-fizzbuzz.py`: FizzBuzz implementation in Python
- `1-print_square.js`: Square printing implementation in JavaScript
- `2-sort.rb`: Sorting implementation in Ruby
- `3-user.py`: User class implementation in Python
- `4-delete_dnodeint/`: Double linked list implementation in C

## Notes

This project is completely optional. Completing any part of it will add a project grade of over 100% to your average. However, if your current average is greater than your score on this project, your average might decrease.
