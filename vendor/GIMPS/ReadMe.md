[License]://creativecommons.org/licenses/by-nc-sa/4.0/deed.ru

Приложение|Редакция|Версия|Дата|Язык
---|---|---|---|---
Prime95 <sup>[www]</sup>|Release|29.4|2018-02-09|en

[www]://mersenne.org/download/ "Download"

### Краткое описание

Официальное приложение проекта GIMPS (Great Internet Mersenne Prime Search) осуществляет поиск простых чисел 
*среди* чисел Мерсенна (2<sup>x</sup>-1). Для поиска требуются современные компьютеры, потому как сложность 
поиска быстро возрастает.

Помимо поиска [простых чисел Мерсенна] используя различные [методы] можно вычислить простые множители 
(сомножители, факторы) чисел Мерсенна. Каждое число Мерсенна имеет очень мало сомножителей.  
Поиск сомножителей методами P-1 (алгоритм Полларда) и ECM (метод эллиптических кривых) требует свободной 
памяти, потому в случае недостатка памяти вычисления остановятся, а в графе `Stage` назначенных заданиях 
появятся *метки* без указания процентов. Зато эти методы находят простые множители на несколько порядков 
длиннее.  

Проверка PRP (вероятное простое) с большой вероятностью укажет, если все простые множители будут найдены, 
или число Мерсенна не имеет сомножителей и является простым (данный метод заменил тест LL).

Любой метод добавляет очков в проекте GIMPS.

[простых чисел Мерсенна]://mersenne.org/primes/
[методы]://www.mersenne.org/various/math.php

---

# Содержание репозитория

- ***TrialFactoring.md*** - таблица найденных простых делителей
- ***ReadMe.md*** - описание и рекомендации по проекту GIMPS

# Дополнительные приложения

### :cyclone: Приложения для поиска простых сомножителей на GPU

1. [gpuOwL] a tiny OpenCL  
1. [mfaktc] a CUDA  
2. [mfakto] an OpenCL  

[gpuOwL]:http://www.mersenneforum.org/showthread.php?t=22204
[mfaktc]:http://www.mersenneforum.org/showthread.php?t=12827
[mfakto]:http://www.mersenneforum.org/showthread.php?t=15646

# 