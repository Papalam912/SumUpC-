# Решение

Вводим первоначальный массив строк.
Проверяем не является ли он NULL, если является то заново вводим массив строк
Присвоим massive[] данные массива разделив строку методом split.
Массив используется в методе ArrayLessThreeSymbol
Присуждаем newMassive данные метода ArrayLessThreeSymbol.
Печать newMassive.

## Описание метода ArrayLessThreeSymbol.

Начальные данные массив array[] и счетчик counter = 0.
Проверяем индексы массива циклом for на количество элементов индекса если их количество меньше или равно трём то счетчик увеличивается на единицу.
После окончания цикла создается массив newArray[] равный числу счетчика и добавляется новый элемент j = 0.
Создается новый цикл for который присуждает newArray[] индекса j данные array[] индекса i при условии количество элементов индекса меньше или равно трём и увеличиваем j на единицу.
После цикла выводим массив newArray[].