---
## Front matter
title: "Отчёт по индивидуальному проекту №2"
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

Знакомство и установка DVWA в систему Kali Linux.

# Выполнение лабораторной работы

1. Открываю консоль и ввожу команду *wget https://raw.githubusercontent.com/IamCarron/DVWA-Script/main/Install-DVWA.sh* для скачивания исполняемого файла DVWA (рис. [-@fig:001])

![Скачивание DVWA из Github](image/1.png){ #fig:001 width=70% }

2. Для установленного файла добавляю права на исполнение с помощью команды *chmod +x* (рис. [-@fig:002])

![Права на исполнение](image/2.png){ #fig:002 width=70% }

3. Запускаю от имени суперпользователя скачанный файл командой *sudo ./Install-DVWA.sh*. (рис. [-@fig:003], рис. [-@fig:004])

![Установка DVWA](image/3.png){ #fig:003 width=70% }

![Установка DVWA](image/4.png){ #fig:004 width=70% }

# Выводы

Я узнал о DVWA и поставил ее на систему Kali Linux

# Список литературы{.unnumbered}

::: {#refs}
:::
