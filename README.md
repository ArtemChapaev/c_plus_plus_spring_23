# C++ VK2023

## Чапаев Артем ML-11 

### Ментор: Сергей Ванданов

### Преподаватель: -

# Домашнее задание 1

В домашнем задании необходимо написать код программы, выполняющую определенную задачу в зависимости от варианта.

**Вариант #3**

Необходимо разработать программу, которая обрабатывает данные онлайн сервиса IMDB.  
Датасеты можно скачать на официальном сайте IMDB https://datasets.imdbws.com/  
Описание датасетов находится по ссылке https://www.imdb.com/interfaces/  
Каждый файл представляет из себя сжатый TSV файл, где данные располагаются в строчках,
а поля разделены символом табуляции \t

Скачать датасет по ссылке можно с помощью команды wget, 
например `wget https://datasets.imdbws.com/title.basics.tsv.gz`  
Полученные файлы нужно распаковать `gunzip title.basics.tsv.gz`  

Программа должна принимать необходимые для работы имена распакованных файлов в качестве аргументов 
командной строки и выводить данные в стандартный вывод.  
Программа не должна брать в расчет фильмы для взрослых, и , если в варианте используется рейтинг, 
не должна учитывать рейтинг фильмов с числом оценок меньше 1000.  
Программа не должна использовать интерактивный ввод с клавиатуры, например, "введите имя файла", 
"введите необходимый год", "ведите q чтобы выйти" - такими программами не удобно пользоваться 
и их разработка занимает больше времени.  

**Ваш вариант:**
Вывести русские названия (при наличии) 10 самых рейтинговых фильмов, длительность которых не 
превышает числа минут, переданных в аргументах командной строки