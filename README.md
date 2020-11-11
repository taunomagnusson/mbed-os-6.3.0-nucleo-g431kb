Fork of mbed-os to add support for new target STM32 "NUCLEO-G431KB" Board.

Howto (using mbed-cli):

Alt A:
1. mbed import https://github.com/taunomagnusson/mbed-os-nucleo-g431kb.git
2. cd mbed-os-nucleo-g431kb
3. Add a "main.cpp" file, for example the main.cpp from here: https://github.com/ARMmbed/mbed-os-example-blinky/blob/master/main.cpp
4. mbed compile

Alt B:
1. mkdir g431kb
2. cd g431kb
3. git clone https://github.com/taunomagnusson/mbed-os-nucleo-g431kb.git
4. mv mbed-os-nucleo-g431kb mbed-os
5. mbed new .
6. Add a "main.cpp" file, for example the main.cpp from here: https://github.com/ARMmbed/mbed-os-example-blinky/blob/master/main.cpp
7. mbed compile
