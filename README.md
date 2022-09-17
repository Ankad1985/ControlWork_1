## **Задача**: 
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. 
При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []


## **Решение:**
1. Инициализируем два строковых массива string[] array1 = new string[5] {"1234","123","world","7","Rus"}; string[] array2 = new string[array1.Length], и переменную int j = 0.
2. При помощи цикла FOR проходим по первому массиву array1, индекс i равен нулю, после каждого прохождения по циклу, i увеличиваем на единицу.
3. Проверяем условие задачи: если длина элемента массива array1 с индексом i меньше или равна 3, то записываем его в массив array2 c индексом j, и увеличиваем j на единицу, если условие не выполняется то цикл начинается заново, пока индекс i массива array1 не станет равен длине массива array1.
4. Выводим элементы сформированного массива array2[j] при помощи цикла FOR.  
 