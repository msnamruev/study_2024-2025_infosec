---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Основы инфорционной безопасности"
author: "Намруев Максим Саналович"

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
mainfont: IBM Plex Sans
romanfont: IBM Plex Sans
sansfont: IBM Plex Sans
monofont: IBM Plex Sans
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей.

# Выполнение лабораторной работы

1. Создаю второго пользователя и задаю для него пароль(рис. [-@fig:001]).

![Guest2](image/1.png){#fig:001 width=70%}

2. Добавляю пользователя guest2 в группу guest (рис. [-@fig:002]).

![Добавление пользователя в группу](image/2.png){#fig:002 width=70%}

3. Осущевствляю вход в систему от двух разных пользователей с двух разных консолей(рис. [-@fig:003]).

![Вход](image/3.png){#fig:003 width=70%}

4. Уточняю имя пользователя, его группу, кто в неё входит, и к каким группам он пренадлежит. (рис. [-@fig:004]).

![Название рисунка](image/4.png){#fig:004 width=70%}

![Название рисунка](image/5.png){#fig:005 width=70%}

![Название рисунка](image/6.png){#fig:006 width=70%}

![Название рисунка](image/7.png){#fig:007 width=70%}

![Название рисунка](image/8.png){#fig:008 width=70%}

![Название рисунка](image/9.png){#fig:009 width=70%}

![Название рисунка](image/10.png){#fig:010 width=70%}

5. Сравниваю это с информацией с файле /etc/group(рис. [-@fig:011]).

![Название рисунка](image/11.png){#fig:011 width=70%}

6. От имени пользователя guest2 выполняю регистрацию пользователя guest2 в группе guest и от имени пользователя guest изменяю права, разрешив все действия для пользователей группы(рис. [-@fig:0012]).

![Название рисунка](image/12.png){#fig:012 width=70%}

7. От имени пользователя guest снимаю с директории /home/guest/dir1 все атрибуты(рис. [-@fig:013]).

![Название рисунка](image/13.png){#fig:013 width=70%}

8. Заполняю таблицу (рис. [-@fig:014]).

![Название рисунка](image/14.jpg){#fig:014 width=70%}


# Выводы

8 способов как бросить дрочить хороший альбом!!(рис. [-@fig:015]).

![Название рисунка](image/15.jpg){#fig:015 width=70%}

# Список литературы{.unnumbered}

::: {#refs}
:::
