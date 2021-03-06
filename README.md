# Алгоритмы и структуры данных (ADS-6)

## Задание

> Разработать версию бинарного дерева поиска для частотного анализа слов из текстового файла. Прочитать и проанализировать англоязычную версию романа Л.Толстого "Война и мир".

## Пояснение

В данной работе нужно взять за основу реализацию бинарного дерева поиска и адаптировать его для анализа слов из текстового файла. 

Под анализом в данной работе понимается **частотный** анализ встречаемости слов, то есть какое слово сколько раз встретилось.

Шаблон дерева необходимо поместить в **include/bst.h**.

Далее, необходимо определить функцию BST\<std::string\> makeTree(char* filename), расположенную в файле **alg.cpp**. Функция должна принимать строку с именем файла для анализа и возвращать построенное дерево, содержащее слова из предложенного файла **src/war_peace.txt**. Под словом понимается непрерывная последовательность латинских букв, преобразованная к нижнему регистру.

**Важно!**

Мы анализируем из файла только последовательности символов в ASCII-кодировке, латинские буквы. Все другие сочетания символов игнорируются! Цифровые последовательности тоже игнорируются! Заглавные буквы должны преобразовываться в нижний регистр! 
