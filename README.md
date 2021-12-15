# TaDS - Типы и Структуры Данных

## lab_01 (длинная арифметика)

Смоделировать операцию _умножения двух действительных чисел_ в форме +\-m.n Е +\-K, где суммарная длина мантиссы (m+n) - до 30 значащих цифр, а величина порядка K - до 5 цифр. Результат выдать в форме +\-0.m1 Е +\-K1, где m1 - до 30 значащих цифр, а K1 - до 5 цифр.

## lab_02 (записи с вариантами, обработка таблиц)

Создать таблицу, содержащую не менее 40-ка записей (тип – запись с вариантами). Упорядочить данные в ней по возрастанию ключей, где ключ – любое невариантное поле (по выбору программиста), используя:
 - саму таблицу
 - массив ключей
(возможность добавления и удаления записей в ручном режиме обязательна).

Ввести репертуар _театров_, содержащий: название театра, спектакль, режиссер, диапазон цены билета, тип спектакля: детский – для какого возраста, тип (сказка, пьеса); взрослый – пьеса, драма, комедия); музыкальный – композитор, страна, минимальный возраст, продолжительность). Вывести список всех музыкальных спектаклей для детей указанного воз-раста с продолжительностью меньше указанной.


## lab_03 (обработка разреженных матриц)

Разреженная (содержащая много нулей) матрица хранится в форме 3-х объектов:
 - вектор A содержит значения ненулевых элементов;
 - вектор IA содержит номера _строк_ для элементов вектора A;
 - связный список JA, в элементе Nk которого находится номер компонент
в A и IA, с которых начинается описание _столбца_ Nk матрицы A.
1. Смоделировать операцию _умножения вектора-строки_ и матрицы, хранящихся в этой форме, с получением результата в той же форме. 
2. Произвести операцию умножения, применяя стандартный алгоритм работы с матрицами. 
3. Сравнить время выполнения операций и объем памяти при использовании этих 2-х алгоритмов при различном проценте заполнения матриц. 


## lab_04 (работа со стеком)

Разработать программу работы со стеком, реализующую операции добавления и удаления элементов из стека и отображения текущего состояния стека. Реализовать стек массивом и списком.
Ввести _целые числа в 2 стека_. Используя третий стек _отсортировать_ все введенные данные.


## lab_05 (обработка очередей)

Система массового обслуживания состоит из обслуживающего аппарата (ОА) и очереди заявок.

Заявки поступают в "хвост" очереди по случайному закону с интервалом времени Т1, равномерно распределенным от _0 до 6_ единиц времени (е.в.). В ОА они поступают из "головы" очереди по одной и обслуживаются также равновероятно за время _Т2 от 0 до 1_ е.в., Каждая заявка после ОА с вероятностью _Р = 0.8_ вновь поступает в "хвост" очереди, совершая новый цикл обслуживания, а с вероятностью 1-Р покидает систему (все времена – вещественного типа). В начале процесса в системе заявок нет.
Смоделировать процесс обслуживания до ухода из системы первых 1000 заявок. Выдавать после обслуживания каждых 100 заявок информацию о текущей и средней длине очереди. В конце процесса выдать общее время моделирования и количество вошедших в систему и вышедших из нее заявок. Обеспечить по требованию пользователя выдачу на экран адресов элементов очереди при удалении и добавлении.


## lab_06 (обработка деревьев, хеш-функций)

В текстовом файле содержатся _целые_ числа. Построить ДДП из чисел файла. Вывести его на экран в виде дерева. Сбалансировать полученное дерево и вывести его на экран. Построить хеш-таблицу из чисел файла. Использовать _закрытое хеширование_ для устранения коллизий. Осуществить _добавление_ введенного целого числа, если его там нет, в ДДП, в сбалансированное дерево, в хеш-таблицу и в файл. Сравнить время добавления, объем памяти и количество сравнений при использовании различных (4-х) структур данных. Если количество сравнений в хеш-таблице больше указанного(вводить), то произвести реструктуризацию таблицы, выбрав другую функцию.


## lab_07 (графы)

Найти все вершины графа, к которым от заданной вершины можно добраться по пути не длиннее А.
