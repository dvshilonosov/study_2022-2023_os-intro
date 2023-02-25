---
## Front matter
title: "ОТЧЕТ О ВЫПОЛНЕНИИ ИНДИВИДУАЛЬНОГО ПРОЕКТА. ЭТАП №1"
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

Размещение на Github pages заготовки для персонального сайта.

# Задачи

1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

Скачиваем архив hugo_extended_0.110.0_Linux-64bit.tar.gz с сайта https:://github.com/gohugoio/hugo/releases (рис. [-@fig:001])

![Скачивание архива с исходным файлом hugo](image/1.png){#fig:001 width=70%}

Создаем в домашнем каталоге папку bin, разархивируем скачанный архив и перенесем исходный файл в каталог ~/bin (рис. [-@fig:002])

![~/bin/hugo](image/2.png){#fig:002 width=70%}

Создаем репозиторий с именем "blog" по шаблону wowchemy/starter-hugo-academic (рис. [-@fig:003])

![Создание репозитория "blog"](image/3.png){#fig:003 width=70%}

Переходим в каталог, где располагаются все наши репозитории, связанные с выполнением лабораторных работ (рис. [-@fig:004])

![Переход в рабочую директорию](image/4.png){#fig:004 width=70%}

Клонируем созданный репозиторий "blog" в ~/work (рис. [-@fig:005])

![Клонирование репозитория "blog"](image/5.png){#fig:005 width=70%}

Выполняем команду ~/bin/hugo server (рис. [-@fig:006]) и с помощью полученного локального адреса переходим на веб-сайт (рис. [-@fig:007])

![Команда ~/bin/hugo server и локальный адрес](image/6.png){#fig:006 width=70%}

![Локальный веб-сайт](image/7.png){#fig:007 width=70%}

На нем расположен наш сайт, с шаблоном. Однако доступ к нему будет только у компьютера, который этот сервер запустил. Далее шаги будут направлены на то, чтобы это исправить.

Создаем репозиторий с именем "dvshilonosov.github.io" (рис. [-@fig:008])

![Создание репозитория "dvshilonosov.github.io"](image/8.png){#fig:008 width=70%}

Клонируем созданный репозиторий "dvshilonosov.github.io" в ~/work (рис. [-@fig:009])

![Клонирование репозитория "dvshilonosov.github.io"](image/9.png){#fig:009 width=70%}

Переходим в репозиторий "dvshilonosov.github.io" и создаем ветку "main" (рис. [-@fig:010])

![Создание ветки main](image/10.png){#fig:010 width=70%}

Создаем файл README.md и отправляем все изменения на сервер репозитория "dvshilonosov.github.io" (рис. [-@fig:011])

![Создание файла README.md. Отправка всех изменений на сервер](image/11.png){#fig:011 width=70%}

С помощью mcedit закомментируем каталог "public" в файле ".gitignore" репозитория "blog" (рис. [-@fig:012])

![Комментирование каталога "public" в файле ".gitignore"](image/12.png){#fig:012 width=70%}

Подключаем к репозиторию "dvshilonosov.github.io" модуль-директории "public" репозитория "blog" (рис. [-@fig:013])

![Подключение модуль-директории](image/13.png){#fig:013 width=70%}

Запуск исполняемого файла hugo командой ~/bin/hugo в репозитории "blog" (рис. [-@fig:014])

![Запуск исполняемого файла hugo](image/14.png){#fig:014 width=70%}

Можно заметить, что справа, в папке "public", сгенерировались новые папки и файлы.

Проверим, соединены ли репозитории "blog" и "dvshilonosov.github.io". Для этого введем команду git remote -v (рис. [-@fig:015])

![Проверка соединения репозиториев](image/15.png){#fig:015 width=70%}

Отправим все изменения на сервер (рис. [-@fig:016])

![Отправка всех изменений на сервер](image/16.png){#fig:016 width=70%}

Проверка работоспособности сайта по публичному адресу на основной ОС (рис. [-@fig:017])

![Проверка работоспособности сайта](image/17.png){#fig:017 width=70%}

# Выводы

Были размещены заготовки персонального сайта на Github pages: установлено необходимое ПО, скачан шаблон темы сайта, размещенный на хостинге git, установлены параметры для URLs сайта.
