# Lab1
# Submission Details
In this lab you will create five simple scripts. Write the scripts in codespaces. 
Please note that you must complete the lab during the class hours and show your progress to the professor to receive the marks for the lab.

# Lab Objectives
- Create and execute simple python scripts which require creating and initializing variables, using string methods, print() function, and simple arithmetic operations.

## Lab1a.py
- Open the file lab1a.py.
-  Add the following comments at the top of your script:
```python 
# Author: [Your Name]
# Script Name: lab1a.py
# Description: Demonstrates basic variable usage, string manipulation, and type checking in Python.
```
- Create a variable called `message` and assign it a string value "Welcome to SRT111". Print the variable.
- Use the builtin `type()` function and print the type of this variable.
- Concatenate the variable `message` with another string and print the result, use the `+` for concatenation.
- Create another variable called `x` and assign it the value 10.
- Check its type using `type()` function.
- In the next statement reassign x to the value "hello" and print its type again.
- What did you observe?  Write your observation in comments.
- Run the script from the terminal.
- Take a screenshot showing:
  - Your code
  - Terminal output. This should show your username in the terminal.
- Add this screenshot in a word document under the heading "**Lab1a**". Later you will convert this word document as a pdf and submit it.


## Lab1b.py - User Input & Arithmetic Operations
**Objective**: Practice using the input() function, type conversion, and basic arithmetic operations in Python.

**Instructions:**
- The script should incorporate a variable called `num1` and take its value from user using input() function.
- The script should have another variable named `num2`. The value of `num2` should also be taken from user.
- Convert the variables to float using the `float()` function.
- Perform all the basic arithmatic operations on these two variables and print the output in the following format.
  ```Python
  num1 + num2 = ....
  num1 - num2 = ....
  num1 * num2 = ....
  num1 ** num2 = ....
  num1 / num2 = ....
  num1 // num2 = ....
  num1 % num2 = ....
  ```
- Run the script from the terminal.
- Take a screenshot showing:
  - Your code
  - Terminal output. This should show your username in the terminal.
- Add this screenshot in a word document under the heading "**Lab1b**". 

  

## Lab1c.py — Using the math Module to Calculate
**Objective:** Learn how to import Python modules, take user input, perform type conversion, and use mathematical constants and formulas.
**Instructions**
- Import `math` module.
- The script should include a variable `r`.
- The value of `r` should be a number inputted from the user.
- Convert `r` to an float with `float()` function.
- Using the constant `pi` from `math` module and compute the area of a circle based on `r` being radius.
- Then print the area to the user with the print function.
- Run the script from the terminal.
- Take a screenshot showing:
  - Your code
  - Terminal output. This should show your username in the terminal.
- Add this screenshot in a word document under the heading "**Lab1c**". 

## Lab1d.py — Strings, Indexing, and Formatting
**Objective:** Practice working with strings, string methods, indexing, and formatted output in Python
**Instructions:** 

- Open the file lab1d.py. Fill in the required fields in the comment section.
-	The script should include a variable called `name`.
-	Create a variable called `name` and assign it your name.
-	Use the string method `.upper()` to convert the name to upper case and print it.
-	Create a variable called `age` and assign it your age:
-	Print a birthday message using the .format() method. The message should be: "How are you yourname? Happy xxth birthday!" USe the following statement.
  ``` python
print("How are you {}? Happy {}th birthday!".format(name, age))
```
-	Next create a variable `words`.	The value of `words` should be "The quick brown fox jumps over the lazy dog".
- Using indexing return the first and 17th characters with print function.
- Use negative indexing to extract and print the words "jumps" and "quick":
- Print all charecturs in between index 2-15
- Print "uick brown fox ju" from `words`.
- Run the script from the terminal.
- Take a screenshot showing:
  - Your code
  - Terminal output. This should show your username in the terminal.
- Add this screenshot in a word document under the heading "**Lab1d**". 




## Lab1e.py
- Fill in the required fields in the comment section.
- The script should include a variable called `quantity`.
- The value of `quantity` should be a decimal number of your choice.
- The script should also include a variable called `stock`.
- The value of `stock` should be a decimal number inputted by the user.
- Print the product of `quantity` and `stock` with 4 spaces before the answer using the module % formatting.
- Print the product of `quantity` and `stock` with 7 spaces before the answer and make sure the answer only goes to hundredths using the module % formatting.
- - Run the script from the terminal.
- Take a screenshot showing:
  - Your code
  - Terminal output. This should show your username in the terminal.
- Add this screenshot in a word document under the heading "**Lab1e**". 





## Lab 1 Sign-Off
- Submit the screenshots of each individual script, the screenshot must show your scripts and command line interface and output.
- The screenshot must also show your username on github codespaces.
- Submit individual screenshots of the following scripts:
    - lab1a.py
    - lab1b.py
    - lab1c.py
    - lab1d.py
    - lab1e.py 
