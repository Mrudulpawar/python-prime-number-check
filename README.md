# python-prime-number-check

## About the Project

This project contains a simple Python program to check whether a given number is a prime number or not.

This program is created as part of Python programming homework assigned by **Atul Sir**.

## Objective

To understand and practice:

* `input()` function
* `int()` type casting
* `for` loop
* `if-else` statements
* Modulus (`%`) operator
* Counter variable

## Python Code

```python
no = int(input("Enter no: "))

count = 0

for i in range(1, no + 1):
    if no % i == 0:
        count += 1

if count == 2:
    print(no, "is prime")
else:
    print(no, "no is not prime")
```

## Sample Output

**Example 1:**

```text
Enter no: 7
7 is prime
```

**Example 2:**

```text
Enter no: 6
6 no is not prime
```

## Logic

1. Take a number from the user.
2. Set the counter variable to `0`.
3. Use a `for` loop to check divisibility from `1` to the given number.
4. If the remainder is `0`, increase the counter by `1`.
5. If the counter is equal to `2`, the number is prime.
6. Otherwise, the number is not prime.

## What Is a Prime Number?

A prime number is a number greater than `1` that has exactly two factors: `1` and itself.

Examples: `2, 3, 5, 7, 11, 13`

## Technologies Used

* Python 3
* Visual Studio Code

## Author

**Mrudul Pawar**


