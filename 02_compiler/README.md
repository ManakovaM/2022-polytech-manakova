-O0 (O ноль) - это самые простые и примитивные оптимизации.
-O1 - более сильные оптимизации.
-O2 - оптимизировать все, что можно, но только проверенные и надежные оптимизации.
-O3 - жесткая и насильная оптимизация, применяются экспериментальные методы.
-Os — оптимизация размера
-Ofast — оптимизация скорости
-Og — оптимизация для дебага


complex.cpp
time: 0.556s
size: 17408

-O0 complex.cpp
time: 0.299s
size: 17408

-O1 complex.cpp
time: 0.292s
size: 17262

-O2 complex.cpp
time: 0.285s
size: 17262

-O3 complex.cpp
time: 0.274s
size: 17262

-Os complex.cpp
time: 0.331s
size: 17248

-Ofast complex.cpp
time: 0.351s
size: 18578

-Og complex.cpp
time: 0.349s
size: 17344a
