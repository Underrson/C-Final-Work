## Задача:
### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

## Описание решения:
### 
* Создаем два массива: изначальный и вторый такой же длины. 
* Задаем метод, в котором цикл соразмерен длине массива. (Внутри цикла проверка условия <=3). 
* В случае, если данное условие соблюдается, элемент первого массива заносится в count элементов второго массива. 
* После присвоения переменная count увеличивается на 1 и возвращается к циклу for, в котором i увеличивается на 1. И так проверяется до конца, пока все элементы первого массива не будут проверены.

