# Lab 1 - Introduction to Python Programming

In this lab, you will create and execute several simple Python scripts to practice fundamental programming concepts. The lab is divided into two parts:

- **Part A: In-Class Lab** (must be completed during the scheduled lab period and demonstrated to the professor for grading).
- **Part B: Take-Home Lab** (must be completed independently after class using a local installation of VS Code).

This lab requires students to create and execute Python scripts that use variables, dynamic typing, user input, string methods, arithmetic operations, indexing, slicing, and formatted output.

## Academic Integrity and Use of AI

This lab is intended to assess your individual understanding of Python programming.
You may use AI tools (e.g., ChatGPT, Copilot, Gemini) to help explain concepts or error messages. However, you **must not copy and paste lab questions or obtain complete solutions from AI tools**.

All submitted code must be your own work. You must be able to explain your solution to the professor or TA if requested.

Submitting AI-generated, copied, or shared solutions may result in a grade of zero and may be handled according to the College's Academic Integrity Policy.

## Lab Objectives
- Create and execute basic Python scripts using VS Code or JupyterLab.
- Declare and initialize variables with different data types.
- Observe Python's dynamic typing behavior by reassigning variables and examining their types.
- Use built-in functions such as print(), type(), and input().
- Perform arithmetic operations using numeric data.
- Import and use Python modules.
- Apply string methods such as .upper() and .format().
- Use indexing and slicing to access portions of strings.
- Format numeric output for readability.
- Execute Python programs from the VS Code terminal.
- Document program execution with screenshots.
 
## Submission Instructions

### Part A: In-Class Lab
- Complete all assigned in-class tasks during your scheduled lab.
- Demonstrate your completed work to the professor before leaving the lab.
- The professor may ask you to explain portions of your code.
- No PDF submission is required for Part A unless otherwise instructed.

### Part B: Take-Home Lab

For each task:
1. Write and save your Python script in VS Code.  
2. Run the script using the VS Code terminal
3. Take a screenshot that clearly shows:  
   - Your code in the editor.  
   - The terminal output, including your username visible in the terminal.  
4. Insert the screenshots into a Word document under the heading that matches the task name:  
   - Example: **Task5**, **Task6**, **Task7**, etc.
5. Answer the reflection questions at the end of the lab.
6. Convert the Word document to PDF.  Name the PDF file using your Seneca usernmae `yourusername.pdf`.
7. Submit the PDF file as your final lab submission on Blackboard.

---

# Part A - In-Class Lab (Demonstration Required)

## Task 1 - Variables, Dynamic Typing
**Objective:** To understand how Python handles variable assignment and dynamic typing.

**Instructions:**
- Create a file named `task1.py`.
- Create a variable called `x` and assign it the value 10.
- Print:
   - the value of x
   - the type using the type() function.
- In the next statement reassign x to the value "hello".
- Print the new value of x and its new type.
- Run the script from terminal and observe the output.
- In a comment, write your observation about how Python handles variable types.



## Task 2 - String Concatenation
**Objective:** Learn how to combine strings using the + operator

**Instructions:**
- Create a file named `task2.py`.
- Create a variable called `message` and assign it the string "Welcome to SRT111".
- Print the value of `message`.
- Concatenate message with another string of your choice using the + operator and print the result.
- Run the script in the terminal to see the output.
  


## Task 3 - User Input & Arithmetic Operations
**Objective:** Practice using the input() function, type conversion, and basic arithmetic operations in Python.

**Instructions:**
- Create a new python file named `task3.py`.
- Create a variable named `num1` and obtain its value from the user using `input()`.
- Create a variable named `num2` and obtain its value from the user using `input()`.
- Convert both variables to float using the `float()` function.
- Perform all the basic arithmetic operations on these two variables and print the output in the following format.
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
 

## Task 4 — Using the math Module to Calculate
**Objective:** Learn how to import Python modules, take user input, perform type conversion, and use mathematical constants and formulas.
**Instructions:**
- Create a file named `task4.py`.
- Import `math` module.
- Create a variable called `r`.
- Obtain the value of `r` from user.
- Convert the value `r` to float.
- Using the constant `pi` from `math` module, compute the area of a circle based on `r` being radius. The formula to compute area of a circle with radius `r` is:
  ``` Python
  Area = π × r²
  ```
- Then print the area to the user with the print function.
- Run the script from the terminal.
  

## Part A Sign-Off

Before leaving the lab, demonstrate all four tasks to the professor.
The professor will verify:

- Script completion
- Successful execution
- Understanding of the code
- Correct output

Students who do not demonstrate their work during the lab period will not receive credit for Part A.

----

# Part B - Take-Home Lab
All tasks in this section must be completed independently using a local installation of VS Code.
For every task, you must provide screenshots showing:

- The source code in VS Code.
- The program output.
- The VS Code terminal displaying your Seneca username.

Failure to include your username in the terminal screenshot may result in a grade of zero for that task.

## Task 5 — Strings Formatting
**Objective:** Practice working with strings, string methods, and formatted output in Python
**Instructions:** 

- Create a file named `task5.py`.
- Create a variable called `name` and assign it your name.
- Convert the value of name to uppercase using the `.upper()` method.
- Print the uppercase version of the name
- Create a variable called `age` and assign it your age:
- Print a birthday message using the .format() method. The message should be: "How are you `yourname`? Happy xxth birthday!" Use the following statement.
  ``` Python
   print("How are you {}? Happy {}th birthday!".format(name, age))
   ```
- Run your script in the terminal to verify the output.
  
## Task 6 — Strings, Indexing, and Formatting
**Objective:** Practice accessing individual characters and slices of a string
**Instructions:** 

- Create a file named `task6.py`.
- Create the following variable.
  ```Python
     words = "The quick brown fox jumps over the lazy dog"
  ```
- Using indexing print:
 - the first character.
 - the seventeenth character. 
- Use slicing print the words "jumps" and "quick":
- Print all characters between index position 2 and 15.
- Print the substring: "uick brown fox ju".
- Run the script from the terminal to verify the output.


## Task 7 - Decimal Numbers & String Formatting
**Objective:** Practice working with decimal numbers and formatting output using `.format()` and `{}` placeholders in Python.
**Instructions:** 

- Create a file named `task7.py`.
- Create a variable called `quantity` and assign it a decimal value of your choice.
- Create a variable called `stock` and get its value from the user using `input()` and convert it to a float.
- **Format output using .format()**
  - Print the product of `quantity` and `stock` using {} placeholders using the following statement:
    ```Python
    print("Product: {}".format(quantity * stock))
    ```
  - Print the product again, but this time rounded to two decimal places using {:.2f}:
- Run your script from the terminal to verify the output.


## Task 8 - Practice tracing Python code
**Objective:** Practice tracing Python code, understanding variable assignments, data types, arithmetic operations, and string manipulation.
**Instructions:** 

- Create a file named `task8.py`.
- Assign the variables shown below.
``` Python
  x = 10
  y = 3
  print("A:", x + y)
  print("B:", x / y)
  x = "10"
  print("C:", x * 3)
  name = "Python"
  print("D:", name[0])
  print("E:", name[-1])
  print("F:", name[1:4])
 ```
- Before running the program, add comments to the file predicting the output for each line labeled:
  - A
  - B
  - C
  - D
  - E
  - F
- Run the program and compare the actual results with your predictions.
- Why does x * 3 work after x is reassigned to "10"?

---

### Reflection
At the end of your word document, answer the following questions in your own words. Use 2-4 sentences for each question.
1. In your own words, what is **dynamic typing** in Python? How did you see it in action in these exercises?  
2. What is the difference between **indexing** and **slicing** when working with strings?   
3. What are your key takeaways from this lab? 

## Part B Sign-Off
- Submit a PDF named using your Seneca username, **<your-username>.pdf** on *Blackbaord*.
- Your PDF must include:
    - Task 5 screenshot(s)
    - Task 6 screenshot(s)
    - Task 7 screenshot(s)
    - Task 8 screenshot(s)
    - Reflection questions
- Ensure the code and output are clearly readable. Screenshots should be high-resolution (minimum 800x600) and not blurry.
- Blurry or unreadable submissions will be returned for redo. Resubmissions will only be graded as "**Satisfactory**" with a grade of 0, provided the work is satisfactory. 
