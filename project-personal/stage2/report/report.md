---
## Front matter
title: "Отчёт по 2 этапу проекта"
subtitle: "Информационная безопасность"
author: "Канева Екатерина, НКАбд-02-22"

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

Установить и настроить DVWA.

# Выполнение

Сначала я клонировала репозиторий (рис. [-@fig:1]):

![Клонирование репозитория DVWA.](image/1.png){#fig:1 width=70%}

Далее я запустила apache (рис. [-@fig:2]) и проверила его работу (рис. [-@fig:3]):

![Запуск apache.](image/2.png){#fig:2 width=70%}

![Открытие apache.](image/3.png){#fig:3 width=70%}

Потом я создала файл конфигурации (рис. [-@fig:4]):

![Создание config-файла.](image/4.png){#fig:4 width=70%}

Открыла страницу DVWA (рис. [-@fig:5]):

![Запуск DVWA.](image/5.png){#fig:5 width=70%}

После этого я запустила БД и настроила (рис. [-@fig:6] и [-@fig:7]):

![Запуск БД.](image/6.png){#fig:6 width=70%}

![Настройка БД.](image/7.png){#fig:7 width=70%}

Потом я вошла в нового пользователя БД (рис. [-@fig:8]):

![Авторизация в БД.](image/10.png){#fig:8 width=70%}

Была создана БД в DVWA (рис. [-@fig:9]):

![Создание БД в DVWA.](image/9.png){#fig:9 width=70%}

На этиом установка и настройка были завершены.

# Выводы

Установили и настроили DVWA.