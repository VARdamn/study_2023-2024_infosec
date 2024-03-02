---
## Front matter
title: "Отчёт по индивидуальному проекту №1"
subtitle: "Дисциплина: Основы информационной безопасности"
author: "Барсегян Вардан Левонович НПИбд-01-22"

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
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: Arial
romanfont: Arial
sansfont: Arial
monofont: Arial
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

Установка дистрибутива Kali Linux.

# Выполнение лабораторной работы

1. На сайте kali.org выбираю готовую ВМ kali linux для VirtualBox (рис. [-@fig:001])

![Установка kali](image/1.png){ #fig:001 width=70% }

2. Далее, извлекаю архив и запускаю .vbox файл, который добавляет новую ВМ kali linux. (рис. [-@fig:002])

![Извлечение ВМ](image/2.png){ #fig:002 width=70% }

3. Запускаю виртуальную машину (рис. [-@fig:003])

![Запуск ВМ](image/3.png){ #fig:003 width=70% }

4. При входе, ввожу логин *kali* и пароль *kali* (рис. [-@fig:004])

![Вход](image/4.png){ #fig:004 width=70% }

# Выводы

Я установил виртуальную машину на дистрибутиве kali linux.