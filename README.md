# Accept-a-positive-number-and-display-a-positive-even-number-within-its-range
#  Positive Even Number Display Program

This Python program accepts a **positive number** from the user and prints all the **even numbers** from `1` to that number using a `while` loop. If the user inputs a value less than or equal to zero, the program returns an invalid input message.

---

# Features

- Accepts floating-point input from the user.
- Validates that the input is positive.
- Uses a `while` loop to print **even numbers** within the range.


---

# Program Logic

- Accept user input as a float.
- If the input is less than or equal to 0 ➝ show an invalid message.
- If the input is positive ➝ display all even numbers from 1 to that number.

---

# Sample Code

```python
# Accepting number from the user
n = float(input('Enter the value:'))

# Logic to display positive even numbers within the range
if n <= 0:
    print("The value {} is invalid".format(n))
else:
    if n > 0:
        print("The input value range within {}".format(n))
        i = 1
        while n >= i:
            if i % 2 == 0:
                print("\t {}".format(i))
            i = i + 1
    print("The program is over")
