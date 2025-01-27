# Что   метод в  js?
### метод -это это свойство, которое содержит определение функции.
### Методы в JavaScript — это функции, хранящиеся в качестве свойств объекта.
### Доступ к методу объекта осуществляется с помощью синтаксиса: `objectName.methodName()`.

# String
### Объект String Используется для представления последовательности символов и манипулирования ею.
![image](https://github.com/KulaevaSuman/Methods/assets/171818274/5d67b23f-5e4d-4658-81d7-c903d6b6d516)

![image](https://github.com/KulaevaSuman/Methods/assets/171818274/40e1c51c-0cb5-4352-99a2-500e0f4148ec)


# В JavaScript существует множество методов работы со строками. Вот некоторые из них:

![image](https://github.com/KulaevaSuman/Methods/assets/171818274/52b7d3da-1072-4606-82a6-bec593f8029a)


-  Math.charAt() возвращает символ с указанным индексом (позицией) в строке.Индекс первого символа равен 0, второго - 1...
Индекс последнего символа равен длине строки - 1 .

-  Math.at() принимает целое значение и возвращает новую строку.
Этот метод допускает использование положительных и отрицательных целых чисел. 
Отсчет отрицательных целых чисел начинается с последнего символа строки.

- Метод concat() объединяет две или более строк.
Метод concat() возвращает новую строку.
Метод concat() не изменяет исходную строку.
- Метод replace() возвращает новую строку с замененными значениями.
Метод replace() выполняет поиск в строке значения или регулярного выражения.
Метод replace() не изменяет исходную строку.
- Метод replaceAll() возвращает новую строку, в которой все совпадения с шаблоном заменяются
заменой.
- Метод split() разбивает строку на массив подстрок. Метод split()
возвращает новый массив. Метод split() не изменяет исходную строку. Если
в качестве разделителя используется (" "), строка разделяется на слова.
- Метод substring() извлекает из строки символы, расположенные между двумя индексами (позициями), и
возвращает подстроку.
Метод substring() извлекает символы от начала до конца (эксклюзивно).
Метод substring() не изменяет исходную строку.
Если значение start больше значения end, аргументы меняются местами: (4, 1) = (1, 4).
Значения Start или end, меньшие 0, рассматриваются как 0.
- Метод slice() возвращает неполную копию части массива и строки в новый объект array
, выбранный от начала до конца (end не включен), где start и end представляют индекс элементов в
этом массиве
- Метод toLowerCase() преобразует строку в строчные буквы. Метод toLowerCase()
не изменяет исходную строку.
- The toUpperCase() method converts a string to lowercase letters,using this locale
The toUpperCase() method does not change the original string.
- Метод trim() удаляет пробелы с обеих сторон предложений.
Метод trim() не изменяет исходную строку. 

#  JavaScript Methods Number 
Math.floor() - округляет число в наименьшую сторону.

Math.round() - округляет в ближающую сторону.

Math.ceil() - округляет число наибольшую сторону.

Math.max() - находит максимальное число и запускает его.

Math.min() - находит минимальное число и запускает его.

Math.pow - вычисляет степень числа, поднимая второй аргумент в степени первого аргумента

Math.sqrt - вычисляет квадратный корень заданного числа и запускает его.

Math.abs - возращает элемент в противоположенную сторону т.е поолжительную в отрицательную, а отрицательную в положительную.

Math.random - запускает рандомное число с запятой между числами 0 и 1.

Math.isNaN() - функция проверяет, является ли значение NaN (не числом) или нет.-
