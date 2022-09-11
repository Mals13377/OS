---
## Front matter
lang: ru-RU
title: "Именованные каналы"
author: Мальсагов М.А.
institute:
date: 

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---

## Цель работы

Приобретение практических навыков работы с именованными каналами.

---

## Выполнение лабораторной работы

1. Создал файлы **common.h, server.c, client.c, client2.c**. Скопировал основной код из лабораторки и немного подкорректировал его.(рис. [-@fig:001;-@fig:002;-@fig:003;-@fig:004])

![common.h](image/1.png){ #fig:001 width=70% }

---

## Выполнение лабораторной работы

![server.c](image/2.png){ #fig:002 width=70% }

---

## Выполнение лабораторной работы

![client.c](image/3.png){ #fig:003 width=70% }

---

## Выполнение лабораторной работы

![client2.c](image/4.png){ #fig:004 width=70% }

---

## Выполнение лабораторной работы

2. Создал **makefile**. (рис. [-@fig:005])

![makefile](image/5.png){ #fig:005 width=70% }

---

## Выполнение лабораторной работы

3. Запустил makefile, а затем сервер. (рис. [-@fig:006])

![Запуск makefile и server](image/6.png){ #fig:006 width=70% }

---

## Выполнение лабораторной работы

4. Запустил client в отдельном окне терминала.(рис. [-@fig:007])

![Запуск client](image/7.png){ #fig:007 width=70% }

---

## Выводы

Мы научились пользоваться иеннованными каналами.
