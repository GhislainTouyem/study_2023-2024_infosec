---
## Front matter
title: "Отчёт о выполнении. Индивидуальный проект. Этап 1"
subtitle: "Установка Kali Linux"
author: "Туем Гислен."

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

Установить дистрибутив Kali Linux в виртуальную машину.



# Выполнение лабораторной работы


![Сайт загрузки Kali Linux](image/1.jpg){#fig:001 width=70%}


![выбор 64 бит, соответствующих характеристикам моего компьютера](image/2.jpg){#fig:002 width=70%}


![Имя и тип ОС](image/3.jpg){#fig:003 width=70%}


![Объём памяти](image/4.jpg){#fig:004 width=70%}


![имя и размер файла](image/5.jpg){#fig:005 width=70%}


![параметра Дисплей](image/6.jpg){#fig:006 width=70%}


![выбро диске IDE](image/7.jpg){#fig:007 width=70%}


![общи информации](image/8.jpg){#fig:008 width=70%}


![выбрать язык](image/9.jpg){#fig:009 width=70%}


![географическое положение](image/10.jpg){#fig:0010 width=70%}


![выбор программного обеспечения](image/11.jpg){#fig:0011 width=70%}


![создание паролей пользователей](image/12.jpg){#fig:0012 width=70%}


# Выводы

Мы установили Kali Linux и настроили различные настройки. Наша виртуальная машина работоспособна и готова к использованию.

