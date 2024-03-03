---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Этап 1"
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

Размещение на Github pages заготовки для персонального сайта.

# Задание

1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

Загружаю последнюю версию hugo.

![Загрука hugo](image/Screenshot from 2024-03-01 18-45-54.png){#fig:001 width=100%}

Распаковываю архив с hugo.

![Распаковка hugo](image/Screenshot from 2024-03-01 22-45-26.png){#fig:002 width=100%}

Перемещаю hugo в новый каталог.

![Перемещение hugo в новый каталог](image/Screenshot from 2024-03-01 18-50-17.png){#fig:003 width=100%}

Создаю каталог bio-blog в директории work, куда помещаю файлы из темы academic-theme-cv.

![Создание bio-blog](image/Screenshot from 2024-03-01 19-00-57.png){#fig:004 width=100%}

Создаю сайт.

![Создание сайта](image/Screenshot from 2024-03-01 20-05-28.png){#fig:005 width=100%}

Создаю особый репозиторий на гитхабе в формате ...github.io.

![Создание Git Pages](image/Screenshot from 2024-02-29 20-34-44.png){#fig:006 width=100%}

Привязываю AlVed.github.io к своему проекту.

![Привязка репозитория](image/Screenshot from 2024-03-01 20-30-55.png){#fig:007 width=100%}

Проверяю, всё ли получилось, открываю сайт.

![Запуск сайта](image/Screenshot from 2024-03-01 20-17-17.png){#fig:008 width=100%}


# Выводы

В ходе первого этапа индивидуального проекта я разместила на Github pages заготовки для персонального сайта.
