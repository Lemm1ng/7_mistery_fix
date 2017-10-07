# Решатель квадратных уравнений

This is the library which solves quadratic equation

# Как использовать
Functions in the library:
-- get_roots(a, b, c)
Returns roots for the quadratic equation
``` ax^2 + bx + c = 0 ```
Function output:
1) root1, root2 if discriminant > 0
2) root1, None if discriminant == 0
3) None, None if discriminant < 0


# Как запустить
Example:
```import quadratic_equation
$ root1, root2 = quadratic_equation.get_roots(1.0, -2.2., 1.0)  
```
Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
