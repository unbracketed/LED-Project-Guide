Meet the LEDs
===================================

sizes

form factors - strips, SMT, domed 

RGB

specs - mcd, forward voltage, current

LEDs will allow whatever current is available through. That's why resistors (or constant current drivers) are needed. You shouldn't use PWM in place of resistors for example: http://www.instructables.com/id/Ghetto-Pixels-Building-an-open-source-BlinkM/#commentactioncontainer_CF0Q2CTGP7IS5IH

http://www.pcbheaven.com/userpages/LED_driving_and_controlling_methods/?topic=presentation

BlinkM

RGB deserves a little special treatment because they are really 3 lights in one. Common anode vs. common cathode: http://flashgamer.com/arduino/comments/rgb-led-common-cathode-or-common-anode

Hackable Consumer Products
---------------------------

* GE light strings
* IKEA Dioder 

Product Page: http://www.ikea.com/us/en/catalog/products/20119418/
Tutorials: 

* http://marco-difeo.de/2012/03/28/irdioder-ikea-dioder-hack-mit-atmel-und-infrarotempfanger/  

RGB

If you are mixing colors, diffused LEDs might be better otherwise you can see the individual diodes lit.

Exercises
-------------

current measurements and calculations for some basic circuits
