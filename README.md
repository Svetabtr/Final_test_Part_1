# Итоговая работа по блоку Разработчик

Соловьева Светлана
___

## Задача: 
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

*Примеры:*

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”] 
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]  
[“Russia”, “Denmark”, “Kazan”] → []  


## Алгоритм решения задачи:

1. Дать возможность задать строчный массив с клавиатуры пользователю.
2. Преоразовать текстовую строку в массив значений.
3. Выполнить поверку для каждого элемента цикла: количество символов в значении меньше 3 или нет?
    * если да, то записываем этот элемент в новый массив
    * если нет, то пропускаем
4. По окончанию проверки выводим на экран новый массив данных.


**Дополнительные материалы:**

Блок-схема по решению задачи представлена в файле [Блок-схема](<Блок-схема.drawio>).