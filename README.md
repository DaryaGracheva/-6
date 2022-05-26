(Лабораторная работа №5:
Вариант 3

С клавиатуры вводится два числа K и N. Квадратная матрица А(N,N), состоящая из 4-х равных по размерам подматриц, B,C,D,E заполняется случайным образом целыми числами в интервале [-10,10].Формируется матрица F следующим образом: скопировать в нее А и если в С количество положительных элементов в четных столбцах больше, чем количество отрицательных элементов в нечетных столбцах, то поменять местами В и С симметрично, иначе С и Е поменять местами несимметрично. При этом матрица А не меняется. После чего если определитель матрицы А больше суммы диагональных элементов матрицы F, то вычисляется выражение: A*A^T – K * F^(-1), иначе вычисляется выражение (A^(-1) +G-F^(-1))*K, где G-нижняя треугольная матрица, полученная из А. Выводятся по мере формирования А, F и все матричные операции последовательно.)

Исследовать методы и инструменты визуализации данных в Pyton-проектах. Выбрать из библиотек matplotlib и seaborn от 3 до 5 функций для визуализации. Взять в качестве основы программы программу л.р.№5 и дополнить ее выбранными функциями визуализации. Визуализировать надо результирующую матрицу, интерпретируя ее строки как разные наборы для визуализации в виде графиков, для двумерной визуализации – можно взять любую свою интерпретацию (на пример, значения потенциалов на плоскости).

Выполнила студентка группы ИСТбд-12 Грачева Дарья
