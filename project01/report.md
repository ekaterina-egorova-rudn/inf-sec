---
# Front matter
lang: ru-RU
title: "Отчёт по 1 этапу проекта"
subtitle: "Установка Kali Linux"
author: "Екатерина Егорова"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью данной работы является научиться основным способам тестирования веб приложений. Установка Kali Linux на виртуальную машину.

# Выполнение первого этапа проекта

Создаю виртуальную машину

![Создание новой виртуальной машины](image/01.jpg){ #fig:001 width=70% height=70% }

Устанавливаю дистрибутив Kali Linux в виртуальную машину.Добавляю новый привод оптических дисков и выбираю образ

![Дистрибутив Kali Linux в виртуальную машину](image/02.jpg){ #fig:002 width=70% height=70% }

Запускаю виртуальную машину.
Устанавливаю язык для интерфейса и раскладки клавиатуры. Ввожу учетные данные

![Запускаю виртуальную машину](image/03.jpg){ #fig:003 width=70% height=70% }

![Установка языка для интерфейса](image/04.jpg){ #fig:004 width=70% height=70% }

![Установка раскладки клавиатуры](image/05.jpg){ #fig:005 width=70% height=70% }

![Ввод учетных данных](image/06.jpg){ #fig:006 width=70% height=70% }



Перехожу к этапу установки и дожидаюсь его завершения.

![Этап установки](image/07.jpg){ #fig:007 width=70% height=70% }

![Запущенная система](image/08.jpg){ #fig:008 width=70% height=70% }

# Вывод

Мы приобрели практические навыки установки операционной системы на виртуальную машину.

