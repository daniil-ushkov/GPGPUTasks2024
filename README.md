В этом репозитории предложены задания для курса по вычислениям на видеокартах 2024

[Остальные задания](https://github.com/GPGPUCourse/GPGPUTasks2024/).

# Задание 7. Prefix sum

[![Build Status](https://github.com/GPGPUCourse/GPGPUTasks2024/actions/workflows/cmake.yml/badge.svg?branch=task07&event=push)](https://github.com/GPGPUCourse/GPGPUTasks2024/actions/workflows/cmake.yml)

0. Сделать fork проекта
1. Выполнить задания 7.1, 7.2, 7.3
2. Отправить **Pull-request** с названием ```Task07 <Имя> <Фамилия> <Аффиляция>``` (указав вывод каждой программы при исполнении на вашем компьютере - в тройных кавычках для сохранения форматирования)

**Дедлайн**: 23:59 28 октября.

Задание 7.1. Prefix sum
=========

Реализуйте не work-efficient prefix sum (logN уровней, O(NlogN) работы)
Только за эту реализацию можно получить 7/10 баллов

Задание 7.2. Work-efficient prefix sum
=========

Реализуйте work-efficient prefix sum (logN уровней, O(N) работы)
Только за эту реализацию можно получить 10/10 баллов

Задание 7.3. Сравнение
=========

Реализуйте обе реализации и сравните производительность
За это задание можно получить один бонусный балл (суммарно 11/10 баллов)


Файлы: ```src/main_prefix_sum.cpp``` и ```src/cl/prefix_sum.cl```
