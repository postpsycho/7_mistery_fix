# Решатель квадратных уравнений

Функция для решения квадратных уравнений

# Как использовать

Запускаем функцию get_roots(a, b, c) - где a, b, c числа уравнения, для которого нужно найти корни.
Ответ будет в формате число, число - если корней два; число, None - если корней один;  None, None - если решения для уравнения нет.

```python
from quadratic_equation import get_roots
get_roots(1, 2, -3)
```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
