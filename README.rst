Introduction
============

This is a guide intended for hobbyists focused on building small-scale digital lighting projects, 
written from the perspective of a software veteran jumping into the world of microcontrollers and basic digital circuits. 

Why?
----

I took up digital circuits as a semi-serious hobby; small scale light sculptures and custom home installations being the general focus for my learning. 
A couple things I discovered initially: 

* There is a fair jump in knowledge when you're looking to move beyond novice-level blinking a few lights up to 
  individually controlling several or more lights (especially for RGB LEDs). It gets more complicated than just wiring up additional lights. 
* It takes some effort to figure out what you need to know. Even seemingly simple schematics might employ a number of important electrical engineering techniques.
  Connecting the dots and understanding the whys can take some poking around.

I’ve noticed a lot of [redditors](http://reddit.com/r/arduino/) often have similar questions to myself regarding driving LED circuits so this is an attempt to gather up the best bits and pieces I’ve found. 
This guide is an attempt to document my learning and organize the helpful pieces of information I've found in case it might help others. 

Audience
--------

The Arduino and its community appear to be a popular point of entry for newcomers to digital circuits and hobbyists alike. Much of the guide will use Arduino as a starting
point, but the general engineering and programming concepts may be applicable to other hardware choices. 

Hopefully the information will be relevant whether you're hoping to design your own pieces, cobble together kits, have a bit of budget, or are a college student living
on ramen.
