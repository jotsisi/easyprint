# Introduction

With this library, printing will be much easier and more customizable.

# Installation

To download the library, use one of the following commands in your terminal:

- ``pip install easyprint``
- ``pip3 install easyprint``

# Usage

The only function in **easyprint** is `write`. In `write`, you specify the set of elements the program will print by separating them with commas inside parentheses. For example:

```python
import easyprint 

easyprint.write(7, "Python3", 3.14)
```

The output for this example is:
```
7
Python3
3.14
```

Additionally, if we specify a sep (short for separator) in write, the function will print the set separated however you choose. For example:
```python
import easyprint

easyprint.write("I love", "Python3", sep=" ")
```
The output of the program is:
```
I love Python3
```

Another example:
```python
import easyprint

a = int(input())
b = int(input())

easyprint.write("First you wrote", a, "and then", b, sep=" ")
```

If a = 67 and b = 76, the output is:
```
First you wrote 67 and then 76
```

# License
MIT License
