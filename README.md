**Домашнее задание**
работаем с процессами

**Цель:**
работать с процессами

Что нужно сделать?

Задания на выбор:

- написать свою реализацию ps ax используя анализ /proc
Результат ДЗ - рабочий скрипт который можно запустить
- написать свою реализацию lsof
Результат ДЗ - рабочий скрипт который можно запустить
- дописать обработчики сигналов в прилагаемом скрипте, оттестировать, приложить сам скрипт, инструкции по использованию
Результат ДЗ - рабочий скрипт который можно запустить + инструкция по использованию и лог консоли
- реализовать 2 конкурирующих процесса по IO. пробовать запустить с разными ionice
Результат ДЗ - скрипт запускающий 2 процесса с разными ionice, замеряющий время выполнения и лог консоли
- реализовать 2 конкурирующих процесса по CPU. пробовать запустить с разными nice


**Выполнение**

Написал свою реализацию ps ax используя анализ /proc [ps.sh](https://github.com/hellolightSP/otus_hw10/blob/main/ps.sh)
