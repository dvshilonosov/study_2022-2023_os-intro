---
## Front matter
title: "ОТЧЕТ О ВЫПОЛНЕНИИ ЛАБОРАТОРНОЙ РАБОТЫ №3"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

- Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
- В качестве отчёта предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)

# Выполнение лабораторной работы

Так как лабораторная работа №2 была выполнена ранее, перейдем в каталог нашего репозитория, затем в каталог, где находится выполненный отчет и презентация лабораторной работы №2. (рис. [-@fig:001])

![Каталог, в котором расположен репозиторий](image/1.jpg){#fig:001 width=70%}

Проверим, что лабораторная работа действительно выполнена. Для этого посмотрим содержимое каталогов .../os-intro/labs/lab02/report и .../os-intro/labs/lab02/presentation. Убедимся, что все необходимое для отчета выполнения работы есть в наличии. (рис. [-@fig:002])

![Каталог, в котором расположен репозиторий](image/2.jpg){#fig:002 width=70%}

Откроем report.pdf. Убедимся в том, что .pdf-файл непустой, и что титульный лист сделан по шаблону. (рис. [-@fig:003])

![report.pdf](image/3.jpg){#fig:003 width=70%}

То же самое выполним и с файлом presentation.pdf. (рис. [-@fig:004])

![presentation.pdf](image/4.jpg){#fig:004 width=70%}

# Выводы

В процессе работы мы научились оформлять отчеты с помощью легковесного языка разметки Markdown.
