# homework1
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.

Решение:
Задаем массив old ,в котором храняться изначальные строчки
Задаем переменную count в которую мы запишем количество строк подходящих под условие 
Проходимся циклом по массиву old сохраняя в перемнную count количество эллементов соответсвующих условию
Задаем масссив mem с длинной равной count
Проходимся циклом по массиву old и переписываем в массив mem значения соответсвующие условию 
массив mem - итоговый массив 