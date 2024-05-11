---
## Front matter
title: "Отчёта по этапу №3"
subtitle: "индивидуальный проект"
author: "Ведьмина Александра Сергеевна"

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

Добавить к сайту достижения.

# Задание

1. Добавить достижения.
2. Сделать пост о прошедшей неделе.
3. Добавить пост на тему пот выбору.

# Выполнение лабораторной работы

Добавляю информацию о навыках.

![Навыки](image/Screenshot from 2024-03-27 20-42-38.png){#fig:001 width=100%}

Добавляю информацию о достижениях. 

![Достижения](image/Screenshot from 2024-03-28 21-28-53.png){#fig:002 width=100%}

Создаю пост о прошедшей неделе.

![Пост о прошлой неделе](image/Screenshot from 2024-03-28 21-44-07.png){#fig:003 width=100%}

Добавляю пост о языке разметки Markdown.

![Пост о Markdown](image/Screenshot from 2024-03-28 21-54-29.png){#fig:004 width=100%}

# Выводы

В ходе лабораторной работы все поставленные задачи были выполнены.

