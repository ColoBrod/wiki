# C
## `#include <stdio.h>`
~~~c
printf()
scanf()
~~~

# C++

## `#include <iostream>`
Стандартная библиотека для работы с консолью.
~~~cpp
std::cin
std::cout
std::endl
~~~

## `#include <bitset>`
С помощью этой библиотеки можно выводить числа в двоичном формате.
~~~cpp
cout << bitset<8>(1337) << endl;
~~~

## `#include <typeinfo>`
С помощью этой либы можно получить тип данных переменной
~~~cpp
float x = 1.35;
double y = 2.38;
cout << typeid(x*y).name() << endl; 
~~~