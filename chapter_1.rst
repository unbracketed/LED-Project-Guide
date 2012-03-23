Getting Started
===============

* Arduino
* A few LEDs
* A few resistors 220ohm
* Breadboard

Soon

* voltage regulator
* trim pots
* switch / buttons
* More LEDs
* RGB LEDs

* multimeter
* pliers
* cutters
* wire stripper
* wall wart

Later
 
* transistors
* 555 
* Shift registers
* driver ICs
* 

Assumes a basic working knowledge of the Arduino environment and breadboarding basics. 
http://www.ladyada.net/learn/arduino/lesson3.html
Or you can reserve a copy of Arduino Cookbook from the local library

Arduino tutorials
Note: you can use alternative editors


Exercises
-------------

basic light
blink light


Chapter 2 - Electricity and Digital Circuits
------------------------------------------------------

basic elec.
	voltage, current, power
	resistor

voltage divider
2 transitor constant current
source vs. sink (anode, cathode)
Don’t work with mains power.

Exercises
-------------

alternate flashing lights
fader
chaser / sequence


Chapter 3 - Meet the LEDs
-----------------------------------

sizes
form factors - strips, SMT, 
RGB
specs - mcd, forward voltage, current
http://www.pcbheaven.com/userpages/LED_driving_and_controlling_methods/?topic=presentation


Exercises
-------------

current measurements and calculations for some basic circuits

Chapter 4 - Planning Your Project
--------------------------------------------

http://www.reddit.com/r/electronics/comments/r42iu/need_help_with_choosing_driver_for_leds/
considerations: how many run simultaneously, adjust brightness, etc.

figure out limiting factors
cost vs. design + build time vs. form factor requirements

components:
resistor
capacitor
transistor
	mosfets are voltage components
	bjt are current components
http://www.pcbheaven.com/userpages/LED_driving_and_controlling_methods/?topic=worklog&p=3

IC
photoresistor


Chapter - LED circuits
================

arangements
  single, group / array, matrix
  series, parallel
behaviors
  on steady, fade, blink
http://www.pcbheaven.com/userpages/LED_driving_and_controlling_methods/?topic=presentation
http://www.reddit.com/r/electronics/comments/r733u/a_simple_onetransistor_constant_current_circuit/



Chapter - Signals and Multiplexing
=========================

pwm
modulation
PAM
PWM
PDM
http://en.wikipedia.org/wiki/Pulse-amplitude_modulation#Use_in_electronic_drivers_for_LED_lighting
Switching speed and resolution
generating pulses signals with hardware: PWM pins, timer ICs, etc.

multiplexing
calculating duty cycles and available bandwidth

http://www.reddit.com/r/electronics/comments/r733u/a_simple_onetransistor_constant_current_circuit/


libraries
shiftpwm
fastspi


shift registers
drivers 
TLC5940
MAX....
HL1606
LPD6803
size and input comparisons of the ICs
form factor: DIP, SOP14

AVR vs. PIC
http://www.instructables.com/id/Aurora-9x18-RGB-LED-art/step2/Circuit/
I chose PIC24F08KA101 as the controller. It needed to be powerful enough (16 bit), and requires minimum of external parts (no crystal needed to run at the max speed of 32 MHz) to save space.
http://www.reddit.com/r/electronics/comments/qe2wf/what_are_the_downsides_of_using_an_arduino/


http://rideonthespiral.blogspot.com/2012/02/arduino-how-to-power-led-matrices-using.html
http://rideonthespiral.blogspot.com/2012/02/arduino-how-to-power-led-matrices-using_26.html

aurora method

current concerns - sourcing and sinking

common cathode vs. common anode

microcontroller tradeoffs
clock cycles

using timer ICs
