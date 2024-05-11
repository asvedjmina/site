---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "2 этап"
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

- Заполнить личную информацию на сайте
- Сделать пост о прошедшей неделе
- Сделать пост о системе контроля версий Git

# Выполнение работы

Загружаю свою фотографию.

![Загрука фото](image/Screenshot from 2024-03-16 20-10-58.png){#fig:001 width=100%}

Смотрю, что получилось.

![Просмотр сайта](image/Screenshot from 2024-03-16 20-11-32.png){#fig:002 width=100%}

Заполняю личные данные об образовании, интересах, хобби и тд

![Заполнение данных](image/Screenshot from 2024-03-16 20-22-34.png){#fig:003 width=100%}

Запускаю сайт.
![Просмотр сайта](image/Screenshot from 2024-03-16 20-22-48.png){#fig:004 width=100%}

Делаю пост о системе контроля версий Git.

![Пост о git](image/Screenshot from 2024-03-17 00-54-06.png){#fig:005 width=100%}

Делаю пост о прошедшей неделе.

![Пост о прошлой неделе](image/Screenshot from 2024-03-17 01-08-58.png){#fig:006 width=100%}

Смотрю, что получилось.

![Просмотр сайта](image/Screenshot from 2024-03-17 01-17-55.png){#fig:007 width=100%}


