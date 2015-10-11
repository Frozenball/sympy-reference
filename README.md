# Sympy reference

````python
from sympy import *
init_printing()

x, y, z = symbols('x y z')
f = x**2 + E**(y + z)
ff = diff(f, x)
N = Matrix([(1,2), (3,4)])

result = f.subs({x: 2, y: 3, z: 1})
N(result)

````
