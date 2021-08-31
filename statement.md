# Introduction to Python

## What is Python ?
Python is a high-level programming language, with applications in numerous areas, including web programming, scripting, scientific computing, and artificial intelligence!

It is very popular and used by organizations such as Google, NASA, the CIA, and Disney.

## Printing text

Let's start off by creating a short program that displays "Hello world!".
In Python, we use the `print` statement to output text.

Syntax:`print("Something Here")`

```python runnable
print('Hello World!')
```

## Simple Operations

Python has the capability of carrying out calculations.

They are all similar to normal mathematical functions.

Some Basic Operators
|Symbol | Operation |
|-------|----------|
|`+` | Addition |
|`-` | Subtraction |
|`*` | Multiplication |
|`/` | Division |
|`%` | Modulus |

Enter a calculation directly into the print statement:

```python runnable
print(2 + 2) # additions
print(5 - 3) # subtraction
print(5 * 5) # multiplication
print(25 / 5) # division
print(10 % 3) # modulus
```

## Comments 
Comments can be used to explain Python code, make the code more readable, prevent execution when testing code.

Comments starts with a #, and Python will ignore them.It can be placed at the end of a line, and Python will ignore the rest of the line. 

```python runnable
# this is a new line comment
print("Hi,there") # this is a inline commment
#print("This print won't work")
```

Multiline Comments:
Python does not really have a syntax for multi line comments.

To add a multiline comment you could insert a # for each line:

```python runnable
# this is 
# a 
# multiline comment
print("Multiline Comment")
```

Since Python will ignore string literals that are not assigned to a variable, you can add a multiline string (triple quotes) in your code, and place your comment inside it. This is called a docstring.

```python runnable
"""
    This is called a doctring
   Treated as a multiline comment
"""
print("Docstring")
```

## A Small Test

* why is this not working ??
  ```python runnable
   print("Hello World")
   ```

* What worng with this program ??
  ```python runnable
  #print("You have learnt print, operation, comments")
  ```
