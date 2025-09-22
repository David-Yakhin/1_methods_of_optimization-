# Проект «Методы оптимизации»

Реализация различных методов оптимизации для функций с одной переменной.


##  Реализованные методы

### Notebook 2: Advanced Methods  
- Метод Ньютона с использованием второй производной
- Метод деления отрезка пополам
- Метод ломаной линии
- Градиентный спуск
- Линейное программирование (случай n=2)

##  Использование

```python
# Пример использования
methods_min = Methods_min(a, b, eps)
result = methods_min.gradient(x0, learning_rate, g)

## Functions Tested
f(x) = x² - 5x + 3

Различные ограничения линейного программирования

Requirements
Python 3.8+

NumPy

Matplotlib

Jupyter Notebook