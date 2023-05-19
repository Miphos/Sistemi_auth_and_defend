---
title: "lab1"
format: html
editor: visual
---

## Цель работы 
Получить сведения о системе.

## Исходные данные
1. ПО Manjaro Linux
2. RStudio

## План работы
1. Версия ядра
2. Полные сведения о ядре
3. Используемый дистрибутив
4. Модель процессора
5. Информация о скрытых файлах


## Выполнение заданий

1. Получить версию ядра можно с помощью команды: uname -r
```
{bash}

uname -r
```
![Версия ядра](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/uname_r.png)

2. Полные сведения о ядре: uname -a
```
{bash}

uname -a
```

![Полные сведения о ядре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/uname_a.png)

3. Используемый дистрибутив: lsb_release -a
```
{bash}

lsb_release -a
```
![Полные сведения о ядре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/lsb_release_a.png)

4. Информация о процессоре: cat /proc/cpuinfo
```
{bash}

cat /proc/cpuinfo
```
![ИНформация о процессоре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/cpu_info_0.png)

![Инфомарция о процессоре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/cpu_info_1.png)

![Инфомарция о процессоре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/cpu_info_2.png)

![Инфомарция о процессоре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/cpu_info_3.png)

![Инфомарция о процессоре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/cpu_info_4.png)

![Инфомарция о процессоре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/cpu_info_5.png)

![Инфомарция о процессоре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/cpu_info_6.png)

![Инфомарция о процессоре](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/cpu_info_7.png)

5. Модель процессора: cat /proc/cpuinfo | grep "model name"
```
{bash}

cat /proc/cpuinfo \| grep "model name"
```
![Инфомарция о модели процессора](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/gerp%20model%20name.png)

6. Скрытые файлы: ls -a
```
{bash}

ls -a
```
![Скрытые файлы](https://github.com/Miphos/Sistemi_auth_and_defend/blob/main/Lab_1/Screenshots/ls_a.png)

## Результат
В ходе выполнения лабароторной работы смог получить сведения об используемой системе.

## Вывод
Научился получать сведения о системе Manjaro Linux.
