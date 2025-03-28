# Мультитул для программистов

Это приложение на Python с использованием библиотеки PyQt5 позволяет шифровать и дешифровать текст с помощью двух методов: шифра Цезаря и шифра Виженера. В будущем планируется добавить функционал перевода чисел между системами счисления и профессиональный калькулятор.

## Описание

Приложение предоставляет простой графический интерфейс для выбора метода шифрования (Цезарь или Виженер), действия (шифрование или дешифрование), ввода текста и ключа. Результат отображается в текстовом поле.

### Методы шифрования

1. **Шифр Цезаря**:
   - Шифрование: каждый символ текста сдвигается на определенное количество позиций в алфавите.
   - Дешифрование: каждый символ текста сдвигается обратно на то же количество позиций.

2. **Шифр Виженера**:
   - Шифрование: каждый символ текста сдвигается на позицию, соответствующую символу ключа.
   - Дешифрование: каждый символ текста сдвигается обратно на позицию, соответствующую символу ключа.

## Планы на будущее

В следующих версиях приложения планируется добавить следующие функции:

1. **Перевод чисел между системами счисления**:
   - Поддержка перевода чисел между двоичной, восьмеричной, десятичной и шестнадцатеричной системами счисления.
   - Простой и интуитивно понятный интерфейс для ввода чисел и выбора систем счисления.

3. **Профессиональный калькулятор**:
   - Поддержка базовых арифметических операций (сложение, вычитание, умножение, деление).
   - Расширенные функции: тригонометрия, логарифмы, возведение в степень, извлечение корня.
   - Возможность работы с комплексными числами и матрицами.
4. **Добавление других шифров таких как**:
   -RSA
5. **Локализация приложения на нескольео языков**
   -Как минимум Русский и английский
6. **Генератор паролей и база для их хранения**

## Установка:

1. **Убедитесь, что у вас установлен Python 3.x.**
2. **Установите необходимые зависимости:**

   ```
   pip install PyQt5
3. **Склонируйте репозиторий:**
   ```
   git clone https://github.com/Magmucot/Multitul-for-pragrammists.git
   cd Multitul

