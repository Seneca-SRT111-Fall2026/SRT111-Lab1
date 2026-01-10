# Lab1

In this lab you will create seven simple scripts. Write the scripts in codespaces. This lab requires students to create and execute simple python scripts which require creating and initializing variables, dynamic typing, using string methods, print() function, and simple arithmetic operations.

---
## Lab Objectives
- Create and execute basic Python scripts using GitHub Codespaces.
- Declare and initialize variables with different data types (e.g., strings, integers, floats).
- Observe Python’s dynamic typing behavior by reassigning variables and inspecting their types.
- Use built-in functions such as print(), type(), and input() to interact with the user and inspect data.
- Apply string methods like .upper() and .format() for text manipulation and output formatting.
- Perform arithmetic operations including addition, subtraction, multiplication, division, exponentiation, and modulus.
- Use the math module to access mathematical constants and functions.
- Understand and apply indexing and slicing to extract specific characters or substrings from a string.
- Format numerical output using the % operator for alignment and precision control.
- Document and present code execution results through screenshots and organized submission.
---
# Submission Instructions
For each task:
1. **Write the script** in Codespaces.  
2. **Run the script** from the **terminal**.  
3. **Take a screenshot** that clearly shows:  
   - Your **code** in the editor.  
   - The **terminal output**, including your **username** visible in the terminal.  
4. **Insert the screenshot** into a Word document under the heading that matches the task name:  
   - Example: **Task1**, **Task2**, **Task3**, etc.  
6. **Submit the PDF file** as your final lab submission on Blackbaord.
---

## Task1 - Variables, Dynamic Typing
**Objective**: To understand how Python handles variable assignment and dynamic typing.

**Instructions:**
- Open the file `task1.py` and fill in the comments.
- Create another variable called `x` and assign it the value 10.
- Print the value of x and its type using the type() function.
- In the next statement reassign x to the value "hello".
- Print the new value of x and its type
- In a comment, write your observation about how Python handles variable types.
---
## Task2 - String Concatenation
**Objective**: Learn how to combine strings using the + operator
**Instructions:**
- Open the file `task2.py` and fill in the comments.
- Create a variable message and assign it the string "Welcome to SRT111".
- Print the value of message.
- Concatenate message with another string of your choice using the + operator and print the result.
- Run the script in the terminal to see the output.
  
---

## Task3 - User Input & Arithmetic Operations
**Objective**: Practice using the input() function, type conversion, and basic arithmetic operations in Python.

**Instructions:**
- Create a new python file with name `task3.py` and add the required comments as you did in the last two tasks.
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
--- 

## Task4 — Using the math Module to Calculate
**Objective:** Learn how to import Python modules, take user input, perform type conversion, and use mathematical constants and formulas.
**Instructions**
- Create a new python file for this task and give it a name following the convention of previous task files.
- Import `math` module.
- The script should include a variable `r`.
- The value of `r` should be a number inputted from the user.
- Convert `r` to an float with `float()` function.
- Using the constant `pi` from `math` module and compute the area of a circle based on `r` being radius.
- Then print the area to the user with the print function.
- Run the script from the terminal.
---
## Task 5 — Strings Formatting
**Objective:** Practice working with strings, string methods, and formatted output in Python
**Instructions:** 
- Create a new python file for this task and give it a name following the convention of previous task files.
- Create a variable called `name` and assign it your name.
- Use the string method `.upper()` to convert the `name` to upper case and print it.
- Create a variable called `age` and assign it your age:
- Print a birthday message using the .format() method. The message should be: "How are you `yourname`? Happy xxth birthday!" USe the following statement.
  ``` python
   print("How are you {}? Happy {}th birthday!".format(name, age))
   ```
  - Run your script in the terminal to verify the output.
---
## Task 6 — Strings, Indexing, and Formatting
**Objective:** Practice accessing individual characters and slices of a string
**Instructions:** 

- Create a variable words with the value
  ```Python
     words = "The quick brown fox jumps over the lazy dog"
  ```
- Using indexing return the first and 17th characters with print function.
- Use negative indexing to extract and print the words "jumps" and "quick":
- Print all charecturs in between index 2-15
- Print "uick brown fox ju" from `words`.
- Run the script from the terminal to verify the output.
---

## Task 8 - Decimal Numbers & String Formatting
**Objective:** Practice working with decimal numbers and formatting output using `.format()` and `{}` placeholders in Python.
**Instructions:** 

- Open a new file named `lab1f.py` (or open it if it already exists).
- Create a variable quantity and assign it a decimal value of your choice.
- Prompt the user to enter a decimal value for stock using input() and convert it to a float.
- **Format output using .format()**
  - Print the product of quantity and stock using {} placeholders using the following statement:
    ```Python
    print("Product: {}".format(quantity * stock))
    ```
  - Print the product again, but this time rounded to two decimal places using {:.2f}:
- Run your script from the terminal to verify the output.
---
### Reflection Questions
At the end of your word docuemnt, answer the following questions in your own words. USe 2-4 sentences for each question.
1. In your own words, what is **dynamic typing** in Python? How did you see it in action in these exercises?  
2. What is the difference between **indexing** and **slicing** when working with strings?   
3. What are your key takeaways from this lab? 

## Lab 1 Sign-Off
- Submit a PDF named using your Seneca username, **<your-username>.pdf** on *Blackbaord*.
- The document must include screenshots of the following scripts and their terminal output, clearly showing your GitHub username:
    - task1.py
    - task2.py
    - task3.py
    - task4.py
    - task5.py
    - task6.py
    - task7.py
- Ensure the code and output are clearly readable. Screenshots should be high-resolution (minimum 800x600) and not blurry.
- Blurry or unreadable submissions will be returned for redo. Resubmissions will only be graded as "**Satisfactory**" with a grade of 0, provided the work is satisfactory. 
