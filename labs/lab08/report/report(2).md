---
## Front matter
title: "ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ № 8"
subtitle: "дисциплина:	Архитектура компьютера"
author: "Лисовская Арина Валерьевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Получение навыков по организации циклов и работе со стеком на языке NASM

# Задание

    1.Символьные и численные данные в NASM
    2.Выполнение арифметических операций в NASM
    3.Выполнение заданий для самостоятельной работы

# Выполнение лабораторной работы

## Символьные и численные данные в NASM

Создадим все рабочие файлы и директории, напишем программу. Ее работа (рис. [-@fig:001]).

<p align="center">![Цикл, выводящий цифры от 5 до 1](image/Снимок экрана от 2023-11-29 15-22-41.png){#fig:001 width=70%}</p>

далее попытаемся уменьшить изначальный индекс на 1. Получим результат, отличный от ожидаемого. Получим N/2 значений.(рис. [-@fig:002])

![рис. 2: Цикл, выводящий нечетные, меньшие 10](image/Снимок экрана от 2023-12-02 00-08-29.png){ #fig:002 width=70% }

Работа программы, которая складывает числа, введенные пользоваталем(рис. 3)(рис. [-@fig:003]) 
![Сложение чисел](image/Снимок экрана от 2023-12-02 00-08-29.png){ #fig:003 width=70% }

Создайте исполняемый файл и запустите его, указав аргументы:(рис. 4) [-@fig:004])

![исполняемый файл](image/Снимок экрана от 2023-11-30 12-11-14.png){ #fig:004 width=70% }

Создаем новый файл 8.3 и запускаем его (рис.5) [-@fig:005])

![исполняемый файл](image/Снимок экрана от 2023-12-02 00-41-44.png){ #fig:005 width=70% }

## Задание для самостоятельной работы
(Вар 15)

работа программы, складывающей значения формулы. рис. [-@fig:006]) 

![ее работа](image/Снимок экрана от 2023-12-02 02-45-06.png){ #fig:006 width=70% } 

# Выводы
Были получены по организации циклов и работе со стеком на языке NASM.
