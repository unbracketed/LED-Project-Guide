Getting Started
===========================

Introduction
------------

Your learning curve might depend on what your intellectual needs and goals are. 
Decide where you stand on the spectrum of using kits to make things for your own satisfaction vs. learning the fundamentals in order to be able to execute your creative whims. 
Temper that with the fact that mastering a technical field like digital circuits takes years of full-time dedication. 
Do you like songbooks or do you study music theory? Do you follow recipes or prefer baking from scratch? 

I don't think you need to be a technical genius to be successful. An intimidating part of being a novice is the dizzying array of options with various tradeoffs 
to consider in how you accomplish your project.

* Cost of materials
* Form factor - both of the individual LEDs as well as the finished product as a whole.
* Ease of construction vs. design + programming + wiring + testing labor time.
* Willingness to compromise on any of the above in order to have something working. 


Learning Foundations
---------------------

The knowledge you'll need can vary greatly depending on your goals. If you plan to take any bit of DIY approach, you'll want to start with some basics.

Basic algebra is adequate for beginner digital circuit applications. You'll definitely want to spend some time going through intro to electronics and/or Arduino tutorials. 
You'll need some basic familiarity with a handful of components (resistors, capacitors, transistors, voltage regulators) and an understanding of 
how the properties of Ohm's law relate to each. I'd recommend this even if your goal is just to build schematics you find online. 

If you're looking to program lights in fancy patterns you will run into some need to dip into various maths as well as some non-trivial programming. 
The more sophisticated your creative needs are, the more you'll need to be able to translate general mathematical concepts into specialized programming 
(changing light color and brightness according to the value of math equations over time).

Plan for a little time practicing with basic breadboard wiring. The simple act of wiring up your first circuits will help you realize how little you actually know.  

The thing **about getting beyond a few lights** is:

* You **run out of pins** on the microcontroller. You can still use the single microcontroller but you'll need to learn some more principles. 
* Your circuit and chips have to start dealing with (relatively) **a lot of current**. Combining a desire to keep minimal (and cheap) hardware, many lights, and nice aesthetics means spending some time learning some engineering. 
* You'll want to consider **using some supporting chips** and components to help drive the LEDs. This means more learning time, design time, and build time. For some applications the extra hardware will be required.
* **Cost and time** become real factors. For a beginner who may just want to order roughly the parts necessary for some small projects, the cost per light can run from a couple to several dollars when you factor in the supporting components. A project with 25 RGB lights can easily run $50-$100 and at least several hours in design and build time for a novice. I'm just talking about the small 5mm lights here. If you want higher power lights - enough to make an impact in large rooms or small outdoor spaces - costs can run several times higher if you're planning to source and build everything yourself.


Materials
---------

First steps

Arduino
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


Prototyping Tips
----------------

Get some header pins so you can plug directly into breadboard
Arduino's funky pin dimensions - adjust the pins 

Diagnostics
-----------

Ways to test LED works

* Plug into pin 13 
* Breadboard with resistor and 9v
* Testing common cathode and common anode RGB LEDs
