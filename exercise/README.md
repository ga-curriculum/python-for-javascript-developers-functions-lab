# ![Python Functions Lab - Exercise](./assets/hero.png)

## Introduction

This lab provides an opportunity to practice defining and calling functions in Python.

If you find yourself stuck during the lab, we encourage you to revisit the lesson materials first. They're designed to provide you with the information and examples that will help you complete the exercises. 

If you've revisited the materials and are still facing challenges, don't hesitate to collaborate with your classmates.

## Lab exercises

Copy and paste each of the following exercises into your `app.py` file. 

To check your work, you can run the following command in your terminal:

```bash
python3 app.py
```

### Exercise 1: `sum_to()`

```python
"""
Exercise 1: sum_to

Write a function named sum_to that accepts a single integer, n, and returns the sum of the integers from 1 to n.

Example: sum_to(6) should return 21.
Example: sum_to(10) should return 55.

Complete the exercise in the space below:
"""

# Your code here

print('Exercise 1:', sum_to(6))
```

### Exercise 2: `is_char_a_vowel`

```python
"""
Exercise 2: is_char_a_vowel

Write a function named is_char_a_vowel that takes a single character as an argument. It should return True if the character is a vowel and False otherwise. For the purposes of this exercise, the character 'y' should not be considered a vowel.

Example: is_char_a_vowel('a') should return True.

Complete the exercise in the space below:
"""

# Your code here

print('Exercise 2:', is_char_a_vowel("a"))
```

### Exercise 3: `largest()`

```python
"""
Exercise 3: largest

Write a function named largest that takes a list of numbers as an argument and returns the largest number in that list.

Example: largest([1, 2, 3, 4, 0]) should return 4.
Example: largest([10, 4, 2, 231, 91, 54]) should return 231.

Complete the exercise in the space below:
"""

# Your code here

print('Exercise 3:', largest([1, 2, 3, 4, 0]))
```

### Exercise 4: `reverse_string`

```python
"""
Exercise 4: reverse_string

Define a function called reverse_string. It should take a string and return it with its characters in reverse order. 

Example: reverse_string('rockstar') should return the string "ratskcor".

Complete the exercise in the space below:
"""

# Your code here

print('Exercise 4:', reverse_string('rockstar'))
```

### Exercise 5: `check_palindrome()`

```python
"""
Exercise 5: check_palindrome()

Define a function called check_palindrome. It should take a string and return True if the string is a palindrome (reads the same forwards and backwards) and False otherwise.

Example: check_palindrome('radar') should return True.
Example: check_palindrome('taco') should return False.

Complete the exercise in the space below:
"""

# Your code here

print('Exercise 5:', check_palindrome("radar"))
```

### Exercise 6: `occurrences()`

```python
"""
Exercise 6: occurrences

Write a function named occurrences that takes two string arguments as input and counts the number of occurrences of the second string inside the first string.

Example: occurrences('fleep floop', 'e') should return 2.
Example: occurrences('fleep floop', 'p') should return 2.
Example: occurrences('fleep floop', 'ee') should return 1.
Example: occurrences('fleep floop', 'fe') should return 0.

Complete the exercise in the space below:
"""

# Your code here

print('Exercise 6:', occurrences('fleep floop', 'e'))
```

### Exercise 7: `calculate_tip`

```python
"""
Exercise 7: calculate_tip

Create a function called calculate_tip. It should take two arguments: the bill amount and the tip percentage (as a whole number). The function should return the amount of the tip.

Example: calculate_tip(50, 20) should return 10.

Complete the exercise in the space below:
"""

# Your code here

print('Exercise 7:', calculate_tip(50, 20))
```

### Exercise 8: `product()`

```python
"""
Exercise 8: product

Write a function named product that takes an arbitrary number of numbers, multiplies them all together, and returns the product. Review your notes on *args for this exercise.

Example: product(-1, 4) should return -4.
Example: product(2, 5, 5) should return 50.
Example: product(4, 0.5, 5) should return 10.0.

Complete the exercise in the space below:
"""

# Your code here

print('Exercise 8:', product(2, 5, 5))
```