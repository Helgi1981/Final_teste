## 1. Функция CountShortStrings:
- Функция для подсчета количества строк в массиве, длина которых меньше или равна 3 символам.
- **count**: Переменная для хранения количества подходящих строк.
- **foreach**: Цикл для прохода по каждому элементу массива.
- **if (str.Length <= 3)**: Проверка длины строки. Если длина строки меньше или равна 3, увеличиваем счетчик count.
- **return count**: Возвращаем общее количество подходящих строк.

## 2. Функция FilterShortStrings:
- Функция для создания нового массива строк, длина которых меньше или равна 3 символам.
- **count**: Переменная для хранения количества подходящих строк, полученного из функции CountShortStrings.
- **result**: Новый массив строк с размером, равным количеству подходящих строк.
- **index**: Переменная для отслеживания текущего индекса нового массива.
- **foreach**: Цикл для прохода по каждому элементу исходного массива.
- **if (str.Length <= 3)**: Проверка длины строки. Если длина строки меньше или равна 3, добавляем строку в новый массив и увеличиваем индекс index.
- **return result**: Возвращаем новый массив строк.

## 3. initialArray
- Инициализация исходного массива строк. В реальном сценарии этот массив можно было бы вводить с клавиатуры.

## 4. FilterShortStrings
- Вызов функции, которая возвращает новый массив строк, длина которых меньше или равна 3 символам.

## 5. Console.WriteLine
- Выводит результат на экран в формате ["строка1", "строка2", ...].