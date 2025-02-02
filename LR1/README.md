# Лабораторная работа: Сумма элементов вектора

## Описание задачи
Цель данной лабораторной работы — реализация алгоритма сложения элементов вектора с использованием двух подходов:
1. Вычисления на центральном процессоре (CPU).
2. Вычисления на графическом процессоре (GPU) с использованием CUDA.
Входной вектор размером от 1,000 до 10,000,000 элементов.
Элементы вектора — случайные числа с плавающей точкой.
Выводится время выполнения вычислений на CPU и GPU и ускорение.

## Результаты

![image](https://github.com/user-attachments/assets/b1cb5e98-7b99-4221-b404-6c74b83ed62c)

## Выводы
Преимущества GPU: GPU значительно ускоряет вычисления для больших объемов данных. Ускорение достигает 4.48x для векторов размером 10,000,000.
Преимущества CPU: CPU быстрее выполняет вычисления на маленьком размере векторов, потому что тратится много времени на копирование данных и запуск ядра.
