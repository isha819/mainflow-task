🗂️ Description:

This repository contains a series of beginner-level Python programs developed as part of my internship training. Each task was designed to strengthen core programming concepts such as loops, conditionals, string manipulation, and user-defined functions.

In this report, I have included my approach, the challenges I faced, the solution I implemented, and what I learned from each task. The goal was not just to solve problems but to understand how to think through them systematically.


✅ Task 1: Sum of Two Numbers

🔹 Approach:
Begin with a function that takes two user-provided numbers and returns their sum.

🔸 Challenge:
Initially, I used print statements inside the function, which limited reusability. I later learned to use return statements instead.

🔧 Solution:
Created a function calculate_sum(a, b) that accepts two parameters and returns their sum. Input is taken from the user and passed to the function.

📘 What I learned:

The difference between returning a value and printing it

Basics of input handling and user-defined functions

✅ Task 2: Odd or Even Checker

🔹 Approach:
Use the modulo operator to determine if a number is divisible by 2.

🔸 Challenge:
Making sure that the function returns a clear, readable result.

🔧 Solution:
Defined check_odd_even(n) which uses n % 2 to return either "Even" or "Odd".

📘 What I learned:

How conditional logic works in Python

Writing simple, clear decision-based functions

✅ Task 3: Factorial Calculation

🔹 Approach:
Use a loop to multiply numbers from 1 to n to calculate the factorial.

🔸 Challenge:
Handling edge cases such as 0 or negative numbers, which could cause logical errors.

🔧 Solution:
Used a for loop in a function factorial(n) with proper input checks.

📘 What I learned:

Loop structures and iterative logic

Validating user input and handling exceptions

✅ Task 4: Fibonacci Sequence Generator

🔹 Approach:
Generate the sequence by starting from 0 and 1, and adding the previous two numbers.

🔸 Challenge:
Correctly handling the sequence generation for small values like 1 or 2, and avoiding index errors.

🔧 Solution:
Built a function generate_fibonacci(n) that uses a loop to generate the sequence and stores it in a list.

📘 What I learned:

How lists and loops work together

Sequence generation logic and edge case handling

✅ Task 5: Reverse a String

🔹 Approach:
Use string slicing to reverse the characters in a given string.

🔸 Challenge:
Ensuring that the logic works even for strings with spaces or special characters.

🔧 Solution:
Created a function reverse_string(s) that uses slicing (s[::-1]) to return the reversed version.

📘 What I learned:

String manipulation in Python

The power and simplicity of slicing

✅ Task 6: Palindrome Checker

🔹 Approach:
A string is a palindrome if it reads the same forward and backward.

🔸 Challenge:
Ensuring the comparison is case-insensitive and ignoring extra spaces if needed.

🔧 Solution:
Built a function is_palindrome(s) that converts the string to lowercase and compares it to its reverse.

📘 What I learned:

Input normalization techniques

Real-life use cases of string comparison

✅ Task 7: Leap Year Checker

🔹 Approach:
Use the leap year rules: divisible by 4, but not by 100 unless divisible by 400.

🔸 Challenge:
Structuring the nested conditions cleanly to account for all rules.

🔧 Solution:
Created a function is_leap_year(year) that implements the correct conditional logic.

📘 What I learned:

Nested if-else structures

Applying real-world rules in code

✅ Task 8: Armstrong Number Checker

🔹 Approach:
A number is an Armstrong number if the sum of its digits raised to the power of the number of digits equals the original number.

🔸 Challenge:
Extracting each digit, raising it to the correct power, and summing them accurately.

🔧 Solution:
Implemented is_armstrong(n) that uses string conversion and a loop to perform the calculation.

📘 What I learned:

Type conversions between strings and integers

Digit-wise operations using loops

✅ Task 9: Caesar Cipher (Encryption/Decryption)

🔹 Approach:
Each character in the message is shifted by a fixed number (key) to create a simple substitution cipher.

🔸 Challenge:
Handling both uppercase and lowercase letters, while leaving non-letter characters unchanged. Also needed to wrap around after 'z'.

🔧 Solution:
Created encrypt_caesar(message, key) and decrypt_caesar(message, key) functions using ASCII value manipulation and modular arithmetic.

📘 What I learned:

Basics of cryptography

ASCII-based character operations

The concept of modular wrapping in encryption

🧾 Final Reflections

This internship project helped me develop a strong foundation in:

Writing clean and reusable Python functions

Breaking down problems into manageable steps

Thinking logically before jumping into code

Documenting and explaining my thought process clearly

It also gave me confidence in reading and writing beginner-level programs, while preparing me to tackle more complex tasks ahead.
