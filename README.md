# -4-Python-keyboard-input

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=YourName+%3D+input(%22Enter+name%3A+%22);print(f'Hello+%7BYourName%7D+%F0%9F%98%8A');%23++2+%2B+2+%3D+%3F;num+%3D+int(input(%22answer%3A++%22)))](https://git.io/typing-svg)

## Ввод данных с клавиатуры
В Python, как и в любом другом языке программирования, значения переменным можно присваивать напрямую в коде, например:
```Python
his_name = 'Oliver'
her_name = 'Alisa'

his_age = 19
her_age = 18
```

Однако, мы также можем предоставить пользователям возможность вводить значения самостоятельно, используя функцию `input`. Например:
```Python
his_name = input("Введите имя для него: ")
her_name = input("Введите имя для неё: ")

his_age = int(input("Введите его возраст: "))
her_age = int(input("Введите её возраст: "))
```
В данной конструкции, мы/пользователь сам сможет ввести данные с клавиатуры. Заметьте, что при этом указывается какой тип дынных мы вводим.

**Таблица типов данных с `input`**
| Функция Input       | Описание                                          | Тип данных       | Пример ввода                          |
|---------------------|---------------------------------------------------|------------------|---------------------------------------|
| `input()` или `str(input())`          | Стандартный ввод, возвращает строку               | `str`            | `name = input("Введите имя: ")`       |
| `int(input())`      | Преобразует ввод в целое число                    | `int`            | `age = int(input("Введите возраст: "))` |
| `float(input())`    | Преобразует ввод в число с плавающей точкой       | `float`          | `height = float(input("Введите рост: "))` |
| `bool(input())`     | Преобразует ввод в булевое значение (`True/False`)| `bool`           | `is_student = bool(input("Студент? (True/False): "))` |
| `list(input())`     | Преобразует строку в список символов              | `list`           | `chars = list(input("Введите символы: "))` |
| `tuple(input())`    | Преобразует строку в кортеж символов              | `tuple`          | `chars = tuple(input("Введите символы: "))` |
| `eval(input())`     | Выполняет строку как код Python                   | Разные типы      | `value = eval(input("Введите выражение: "))` |

### Примечания:
- `input()` всегда возвращает строку, поэтому для получения других типов данных необходимо применять преобразование.
- `eval(input())` следует использовать с осторожностью, так как это может быть небезопасно и потенциально выполнить нежелательный код.
- `bool(input())` возвращает `True` для любых непустых строк, а `False` только для пустых строк.
- `input()` и `str(input())` - одинаковые записи, возвращается строка.

## Вывод в консоль или некоторые элементы форматирования


