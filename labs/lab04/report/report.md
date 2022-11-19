---
## Front matter
title: "Шаблон отчёта по лабораторной работе 4"
subtitle: "Язык разметки Markdown"
author: "Сидорова Наталья Андреевна"

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
lot: true # List of tables
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
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Выполнение лабораторной работы
Ход лабораторной работы:
1. Перешла в каталог курса, сформированный при выполнении лабораторной работы 3 и обновила локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды git pull (рис. [-@fig:001])

![Обновление репозитория](image/001.jpg){ #fig:001 width=100% }

2. Перешла в каталог с шаблоном отчета по лабораторной работе 4 и провела компиляцию шаблона с использованием Makefile (рис. [-@fig:002])

![Компиляция шаблона](image/002.jpg){ #fig:002 width=100% }

3. Открыла полученные файлы и проверила их корректность. Удалила полученные файлы (рис. [-@fig:003])

![Удаление файлов](image/003.jpg){ #fig:003 width=100% }

4. Открыла файл report.md и изучила его структуру (рис. [-@fig:004])

![Изучение файла](image/004.jpg){ #fig:004 width=100% }

5. Заполнила отчет и скомпилировала его с помощью Makefile. Проверила корректность полученных файлов  (рис. [-@fig:005])

![Компиляция отчета](image/005.jpg){ #fig:005 width=100% }

6. Загрузила файлы на github.



# Выводы

Освоила процедуры оформления отчетов с помощью легковесного языка разметки Markdown.



::: {#refs}
:::
