# Решатель квадратных уравнений
Модуль для решения квадратных уравнений

# Как использовать

Модуль содержит функцию get_roots которая на вход принимает три параметра a,b,c (коэффиценты уравнения ax^2+bx+c)  
Возвращает пару значений, если корень один, в качестве второго параметра передается `None`,  если корней нет оба параметра равны `None`

```python
>>>from quadratic_equation import get_roots
>>>get_roots(1,2,3)
(None, None)
```
# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск тестов на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
