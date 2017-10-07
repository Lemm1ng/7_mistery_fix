# Quadratic equations solver

This is the library which solves quadratic equations

# How to use
Functions in the library:

-- get_roots(a, b, c)

Returns roots for the quadratic equation
``` ax**2 + bx + c = 0 ```

Function output:
1) root1, root2 if discriminant > 0
2) root1, None if discriminant == 0
3) None, None if discriminant < 0


# How to launch
Example:
```
  import quadratic_equation
  
  
  root1, root2 = quadratic_equation.get_roots(1.0, -2.2, 1.0)  
```

Scrit requires installed Python interpretator, version 3.5

How to launch on Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

The launch on Windows can be done in similar way.

# Project aims

Code is developed for educational purposes in the scope of web-development course ― [DEVMAN.org](https://devman.org)
