---
## Front matter
title: "ОТЧЕТ О ВЫПОЛНЕНИИ ИНДИВИДУАЛЬНОГО ПРОЕКТА. ЭТАП №3"
subtitle: "_дисциплина: Операционные системы_"
author: "Шилоносов Данил Вячеславович"

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
lot: false # List of tables
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
Целью работы является добавление к сайту постов и достижений его владельца.

# Задачи
1. Список достижений.
- Добавить информацию о навыках (Skills).
- Добавить информацию об опыте (Experience).
- Добавить информацию о достижениях (Accomplishments).

2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:
- Легковесные языки разметки.
- Языки разметки. LaTeX.
- Язык разметки Markdown.


# Выполнение лабораторной работы

1. Список достижений:

- Добавим информацию о навыках (Skills) (рис. [-@fig:001], [-@fig:002])

![Добавление информации о навыках в markdown](image/1.png){#fig:001 width=100%}

![Добавление информации о навыках на сайте](image/2.png){#fig:002 width=100%}

- Добавим информацию об опыте (Experience) (рис. [-@fig:003], [-@fig:004])

![Добавление информации об опыте в markdown](image/3.png){#fig:003 width=100%}

![Добавление информации об опыте на сайте](image/4.png){#fig:004 width=100%}

- Добавим информацию о достижениях (Accomplishments) (рис. [-@fig:005], [-@fig:006])

![Добавление информации о достижениях в markdown](image/5.png){#fig:005 width=100%}

![Добавление информации о достижениях на сайте](image/6.png){#fig:006 width=100%}

2. Сделаем пост по прошедшей неделе (рис. [-@fig:007], [-@fig:008])

![Пост по прошедшей неделе в markdown](image/7.png){#fig:007 width=100%}

![Пост по прошедшей неделе на сайте](image/8.png){#fig:008 width=100%}

3. Добавить пост на тему по выбору на тему "Язык разметки Markdown" (рис. [-@fig:009], [-@fig:010])

![Пост а тему по выбору в markdown](image/9.png){#fig:009 width=100%}

![Пост а тему по выбору на сайте](image/10.png){#fig:010 width=100%}

# Выводы
В процессе выполнения этапа индивидуального проекта были добавлены достижения и посты на сайте его владельца.
