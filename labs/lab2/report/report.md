---
## Front matter
title: "Шаблон оростейший втчёта по лабораторной работе № 2"
subtitle: "Дискреционное разграничение прав в Linux. Основные атрибуты"
author: "Туем Гислен"

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

Получение практических навыков работы в консоли с атрибутами фай-
лов, закрепление теоретических основ дискреционного разграничения до-
ступа в современных системах с открытым кодом на базе ОС Linux.

# Задание
1. Создайте нового пользователя "guest" и назначьте ему пароль
2. В этой новой учетной записи создайте папку и файл, а затем потренируйтесь видеть различные способы доступа между ними.
3. Заполните таблицу «установленные права и разрешенные действия»
4. Заполните таблицу "инимальные права для совершения операций"

# Выполнение лабораторной работы



![Создайне учётную запись пользователя guest](image/1.png){#fig:001 width=70%}



![Определиние директорию, в которой вы находимся, командой](image/2.jpg){#fig:002 width=70%}



![указание имени пользователя ](image/3.jpg){#fig:003 width=70%}


![давайте отобразим имя пользователя, его группу, а также группы, в которые входят этот пользователь ](image/4.jpg){#fig:004 width=70%}



![росмотрите файл /etc/passwd](image/5.jpg){#fig:005 width=70%}



![Определите существующие в системе директории командой ls -l /home ](image/6.jpg){#fig:006 width=70%}



![Проверьте, какие расширенные атрибуты установлены на поддиректориях, находящихся в директории /home, командой:lsattr /home](image/7.jpg){#fig:007 width=70%}



![Создайте в домашней директории поддиректорию dir1 командой mkdir dir1](image/8.jpg){#fig:008 width=70%}




![Снимите с директории dir1 все атрибуты командой chmod 000 dir1](image/9.jpg){#fig:009 width=70%}



![опытайтесь создать в директории dir1 файл file1 командой echo "test" > /home/guest/dir1/file1](image/10.jpg){#fig:0010 width=70%}



![заполните таблицу «Установленные права и разрешённые действия»](image/11.jpg){#fig:0011 width=70%}



![заполните таблицу "Минимальные права для совершения операций файл"](image/12.jpg){#fig:0012 width=70%}




# Выводы

После всей этой работы мы увидели, что есть права на чтение, запись и доступ к файлу или документам. Фактически каждый пользователь может предоставлять определенные права другим и по отношению к себе.
