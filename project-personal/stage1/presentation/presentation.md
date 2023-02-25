---
## Front matter
lang: ru-RU
title: ОТЧЕТ О ВЫПОЛНЕНИИ ИНДИВИДУАЛЬНОГО ПРОЕКТА. ЭТАП №1
subtitle: Курс "Операционные Системы"
author:
  - Шилоносов Д.В. , НКАбд-03-22
institute:
  - Российский университет дружбы народов, Москва, Россия
  
date: 25 февраля 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---


## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="40%"}

  * Шилоносов Данил Вячеславович
  * студент группы НКАбд-03-22
  * кафедры Компьютерные и информационные науки 
  * Российский университет дружбы народов
  * [1132221810@pfur.ru](mailto:1132221810@pfur.ru)
  

:::
::: {.column width="30%"}


:::
::::::::::::::


## Цели и задачи
1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.



# Выполнение лабораторной работы 

## Скачивание архива

Скачиваем архив hugo_extended_0.110.0_Linux-64bit.tar.gz с сайта https:://github.com/gohugoio/hugo/releases

![](image/1.png){#fig:001 width=50%}

## Создание директории в домашнем каталоге. Перенос исходного файла hugo

Создаем в домашнем каталоге папку bin, разархивируем скачанный архив и перенесем исходный файл в каталог ~/bin

![](image/2.png){#fig:002 width=50%}

## Создание репозитория "blog"

Создаем репозиторий с именем "blog" по шаблону wowchemy/starter-hugo-academic

![](image/3.png){#fig:003 width=50%}

## Переход в рабочую директорию

Переходим в каталог, где располагаются все наши репозитории, связанные с выполнением лабораторных работ

![](image/4.png){#fig:004 width=50%}

## Клонирование репозитория "blog"

Клонируем созданный репозиторий "blog" в ~/work

![](image/5.png){#fig:005 width=70%}

## Команда ~/bin/hugo server и локальный адрес

Выполняем команду ~/bin/hugo server и с помощью полученного локального адреса переходим на веб-сайт

![](image/6.png){#fig:006 width=50%}

## Команда ~/bin/hugo server и локальный адрес

![](image/7.png){#fig:007 width=500%}

## Создание репозитория "dvshilonosov.github.io"

Создаем репозиторий с именем "dvshilonosov.github.io"

![](image/8.png){#fig:008 width=45%}

## Клонирование репозитория "dvshilonosov.github.io"

Клонируем созданный репозиторий "dvshilonosov.github.io" в ~/work

![](image/9.png){#fig:009 width=70%}

## Создание ветки main

Переходим в репозиторий "dvshilonosov.github.io" и создаем ветку "main"

![](image/10.png){#fig:010 width=60%}

## Создание файла README.md. Отправка всех изменений на сервер

Создаем файл README.md и отправляем все изменения на сервер репозитория "dvshilonosov.github.io"

![](image/11.png){#fig:011 width=50%}

## Комментирование каталога "public" в файле ".gitignore"

С помощью mcedit закомментируем каталог "public" в файле ".gitignore" репозитория "blog"

![](image/12.png){#fig:012 width=30%}

## Подключение модуль-директории

Подключаем к репозиторию "dvshilonosov.github.io" модуль-директории "public" репозитория "blog"

![](image/13.png){#fig:013 width=70%}

## Запуск исполняемого файла hugo

Запуск исполняемого файла hugo командой ~/bin/hugo в репозитории "blog"

![](image/14.png){#fig:014 width=60%}

## Проверка соединения репозиториев

Проверим, соединены ли репозитории "blog" и "dvshilonosov.github.io". Для этого введем команду git remote -v

![](image/15.png){#fig:015 width=60%}

## Отправка всех изменений на сервер

Отправим все изменения на сервер

![](image/16.png){#fig:016 width=50%}

## Проверка работоспособности сайта

Проверка работоспособности сайта по публичному адресу на основной ОС

![](image/17.png){#fig:017 width=50%}



# Результаты

## Выводы

Были размещены заготовки персонального сайта на Github pages: установлено необходимое ПО, скачан шаблон темы сайта, размещенный на хостинге git, установлены параметры для URLs сайта.
