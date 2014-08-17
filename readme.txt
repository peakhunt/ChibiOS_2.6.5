=================================================
This is my modification of ChibiOS 2.6.5

=================================================
It is a tiny cool RTOS and very fun to play with.

=================================================
My first port is for Arduino ATMEGA 2560

You need arduino development kit to build and flash the image.

To flash it on Arduino ATMEGA 2560 board,

a) goto demos/AVR-ArduinoMega2560-GCC
b) make
c) avrdude -patmega2560 -cwiring -P/dev/ttyACM0 -b115200 -D -V -Uflash:w:ch.hex:i

You don't have to erase arduino bootloader since it's like just another
arduino sketch.

enjoy
