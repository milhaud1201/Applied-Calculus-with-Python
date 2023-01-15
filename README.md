# Applied-Calculus-with-Python

**SymPy** is a Python library for working with mathematical expressions in **symbolic** form.

We have seen that Python variables must be assigned a value. However, in math, variables are often used to represent unknowns. `Symbolic computation` allows us to manipulate expressions with variables that are not assigned a value.

Symbolic computation also retains the exact value of expressions, rather than rounding them to decimals. 

The alternative to symbolic computation is `numerical computation`. In numerical computation, all values are represented as either integers or floating-point numbers.

* [SymPy 1.11 documentation](https://docs.sympy.org/latest/tutorials/intro-tutorial/index.html)

## SymPy Code Snippet
---
### substitution
```python
from sympy import *
a = symbols('a')
expression = a**2 - a - 1
# Define the symbol b
b = symbols('b')
# Use subs specifying to replace a with b + 1
expression.subs(a, b + 1)
```
### evaluation as a floating-point number
```python
x = sqrt(5)
x.evalf()
```

