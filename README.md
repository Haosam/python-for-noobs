# python-for-noobs
As a learner of Python, I wanted to practice what I learnt and it would be a good way to do it by writing a repo for it. And this repo is also for my brother to learn programming

Hi! Welcome to Python for noobs. This is just a short introduction to python and how to roughly understand and translate python syntax(code)

## Part 1 - Installation
First you can read this [installation](https://github.com/jarrettyeo/NTUOSS-PythonPipInstallation) as I am too lazy to write the entire installation process.

For Windows users please SKIP to [here](https://github.com/jarrettyeo/NTUOSS-PythonPipInstallation#section-1-installing-python-36x-and-pip)

For Mac users please SKIP to [here](https://github.com/jarrettyeo/NTUOSS-PythonPipInstallation#12-installing-python-36x-and-pip-on-mac)

Please note and install pip. You may need it for further installation packages as you traverse the journey of python.

If you are okay with using the IDLE package for compiling code, go ahead. Otherwise, please head to [Sublime](https://www.sublimetext.com/) to download the sublime code editor. Please note that you have to save your files as name-extension.py, otherwise the python code WILL NOT run. Once you have saved the python code, you may press Ctrl+b to run the code on the sublime platform.

## Part 2 - Right. Into the code
Python code differs a lot as compared to the conventional C, C++ or Java, but they are still similar to some extent.

print('Hello World')
>Hello World

That was the most basic code. But you want to write something more than that right?

How about this, let's write a self introduction of ourselves.

> I am Samuel and welcome to Python for noobs.

> I am 27 this year and I am from NTU

> I am majoring in Electrical and Electronic Engineering.

```
age = 2+(8%3)-1+(4*10)/2+4
name = 'Samuel'
major = 'Electrical and Electronic Engineering'
greeting = 'welcome to python for noobs'

print('I am ', name, 'and', greeting)
print('I am', str(age), 'years old and I am from NTU')
print('I am majoring in', major)
```
## Types and Values
There are 4 types of variables
- Numeric
- String
- Bool
- Sequence
```
a = 9                             # a is a numeric type (integer)
b = 9.145                         # b is a numeric type (float)
c = 4/2/3                         # c is a numeric type (in this case, answer is 0.6666666, so it is a float)
d = 'Pineapple'                   # d is a string
e = 'This is a github file'       # e is a string
x = 3                             # x is an integer
inp = int(input('Enter x: '))     # inp is an input integer (otherwise, it will be string if not declared)
result = bool(inp==x)             # bool comparison
print(result)                     # prints out true of false
```

In python there are libraries and we can call them by writing
```
import decimal
from decimal import *
```

try this
```
from decimal import *

a = Decimal('0.10')
b = Decimal('0.30')

x = a + a + a - b

print('x = ' + str(x))

What is your output?
```
