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

`+`  Addition

`-`  Subtraction

`*`  Multiplication

`/`  Division

`%`  Modulus

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

## Variables

Variables are used to store information e.g. the variable age can hold the information about your age. You would use it like this: age = 18. You can even perform arithematic operation on variables. 

Note: In most programming language `=` is an assignment operator , i.e. to assign an value to a variable

```python runnable
age = 18 # change it to your age, if you want 
print(age)

# to print a variable
```

### Basic Datatypes

Python has a numerous types of **Variables**, to store different types of data.

Types  
`int`    an integer   `e.g: -2304, 0, 3, 5, 7`

`float`  a decimal value (usually only 8 places)   `e.g: 454.656, 0.000003, 0.5486`

`string` Usually considered as anything (numbers, punctuation marks, ASCII/Unicode characters etc.) inside quotes `e.g: "Hello", "1234", "Hello 123! Good Bye. :)"`

`char`   An ASCII/Unicode character e.g: 'A', '1', '$'


### Casting

It's really important to have a variable with the correct datatype, before doing something with it.
To change datatype from one to another is called *casting*.

`int()` To change to int

`float()` To change to float

`str()`  To change to string

`chr()`  To return character related to ASCII/Unicode value

`ord()`  To return the ASCII/Unicode value of a character
