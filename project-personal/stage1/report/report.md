---
## Front matter
title: "Индивидуальный проект этап 1"
subtitle: "Основы информационной безопасности"
author: "Намруев Максим Санлович"

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

Научиться основным способам тестирования веб приложений

# Задание

1. Установите дистрибутив Kali Linux в виртуальную машину.

2. В качестве среды виртуализации предлагается использовать VirtualBox.



# Выполнение лабораторной работы

Открываю VirtualBox (рис. [-@fig:001]).

![VB](image/1.png){#fig:001 width=70%}

Создаю новую ВМ с kali linux(рис. [-@fig:002]).

![kali](image/2.png){#fig:002 width=70%}

Запускаю ВМ(рис. [-@fig:003]).

![Запуск ВМ](image/3.png){#fig:003 width=70%}

Выполняю первичную настройку и задаю пароль для user и root(рис. [-@fig:004]).

![Настройка ВМ](image/4.png){#fig:004 width=70%}

Дожидаюсь установки(рис. [-@fig:005]).

![установка ВМ](image/5.png){#fig:005 width=70%}

# Выводы

я установил кали

