# laboratoty-work-5
## Задания:
 1. Сложение и вычитание матриц А и В 
 2. Умножение матрицы А2 на В2
## Ход работы:
Ввод матриц A и B (временно отключено, для простоты демонстрации)
### Функция суммы:
Создаём нулевую матрицу C с количеством строк и столбцов как у матрицы A
Для каждой строки мтрц А и для каждого элемента в строке(столбца) задаём такой элемент С,
который имеет такой же номер строки и столбца как у А -> приравниваем его 
к сумме элементов А и B с такими же порядковыми номерами
### Функция разности:
Аналогично функции суммы, но вместо суммы элементов A и B берём их разность
Ввод матриц A2 и B2 (временно отключено, для простоты демонстрации)
### Функция произведения:
Создаём нулевую матрицу E с количеством строк и столбцов как у A2
Циклом идём по строкам A2
Вложенным циклом указываем на количество столбиков в B2(== кол-ву строк A2)
Задаём каждый элемент в m-той строке n-том столбце матрицы Е такой, 
который равен сумме:
элемента A2 в m-той строке t-того столбца
(t меняется от 0 до количества строк B2(стобцов A2))
умноженного на элемент B2 в t-той строке n-того столбца
___
Вывод значений
